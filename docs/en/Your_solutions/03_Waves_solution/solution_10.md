# Task 10 – Animation: Wave Sources (Superposition)

## Problem Statement

Create an interactive simulation where point sources of waves can be placed on a 2D field. The waves must follow the equation:

$$
u(\vec{r},t) = \frac{A}{|\vec{r}-\vec{r}_0|^\alpha} \sin(k|\vec{r}-\vec{r}_0| - \omega t)
$$

The simulation must allow setting the attenuation parameter $\alpha \in [0,2]$ and show the interference pattern of all active sources.

## Theory

When multiple wave sources exist in a medium, the resulting displacement at any point $\vec{r}$ is the algebraic sum of the individual displacements (Principle of Superposition):

$$
u_{total}(\vec{r},t) = \sum_{i=1}^{n} u_i(\vec{r},t)
$$

The parameter $\alpha$ determines how the amplitude decays with distance. $\alpha = 0.5$ is typical for circular waves on a surface (energy conservation in 2D), while $\alpha = 1.0$ represents spherical waves in 3D.

## Step-by-Step Solution (Interactive HTML)

Below is the complete, functional code for the simulation.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Wave Source Superposition</title>
    <style>
        body { margin: 0; background: #000; color: #fff; font-family: sans-serif; overflow: hidden; display: flex; flex-direction: column; align-items: center; }
        canvas { background: #000; cursor: crosshair; box-shadow: 0 0 20px rgba(0,255,255,0.2); }
        .controls { padding: 15px; background: rgba(20,20,20,0.9); width: 100%; display: flex; justify-content: center; gap: 20px; border-bottom: 1px solid #333; }
        label { font-size: 12px; text-transform: uppercase; letter-spacing: 1px; }
    </style>
</head>
<body>
    <div class="controls">
        <div>
            <label>Attenuation (α): </label>
            <input type="range" id="alpha" min="0" max="1" step="0.05" value="0.3">
        </div>
        <button onclick="sources = []">Clear Sources</button>
        <div style="font-size: 10px; opacity: 0.7;">Click on Canvas to add Wave Sources</div>
    </div>
    <canvas id="cvs"></canvas>

<script>
    const canvas = document.getElementById('cvs');
    const ctx = canvas.getContext('2d');
    const alphaInput = document.getElementById('alpha');
    
    let w = canvas.width = window.innerWidth;
    let h = canvas.height = window.innerHeight - 60;
    let sources = [];
    let t = 0;

    canvas.addEventListener('mousedown', (e) => {
        sources.push({ x: e.clientX, y: e.clientY - 60 });
    });

    function draw() {
        const a = parseFloat(alphaInput.value);
        const imgData = ctx.createImageData(w, h);
        const data = imgData.data;

        // Downsampling for performance: Calculate every 2nd pixel
        for (let x = 0; x < w; x += 2) {
            for (let y = 0; y < h; y += 2) {
                let sum = 0;
                for (let s of sources) {
                    const dx = x - s.x;
                    const dy = y - s.y;
                    const r = Math.sqrt(dx*dx + dy*dy) + 1;
                    sum += (15 / Math.pow(r, a)) * Math.sin(0.15 * r - t);
                }

                const val = 128 + sum * 20;
                const idx = (x + y * w) * 4;
                
                // Cyan/Blue theme
                data[idx] = val * 0.2;     // R
                data[idx + 1] = val * 0.8; // G
                data[idx + 2] = val;       // B
                data[idx + 3] = 255;       // A

                // Fill neighboring pixels
                data[idx + 4] = data[idx];
                data[idx + 4 + 1] = data[idx + 1];
                data[idx + 4 + 2] = data[idx + 2];
                data[idx + 4 + 3] = 255;
            }
        }
        ctx.putImageData(imgData, 0, 0);
        t += 0.2;
        requestAnimationFrame(draw);
    }
    draw();
</script>
</body>
</html>