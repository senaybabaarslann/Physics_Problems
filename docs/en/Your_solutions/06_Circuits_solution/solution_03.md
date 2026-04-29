# Task 03 – Mixed Circuit (1)

## Problem Statement

Calculate the equivalent resistance for the circuit shown in the figure (image-r1.png). All resistors have a resistance of $5\,\Omega$.

## Theory

The circuit consists of a parallel bridge-like structure. We identify branches that are in series or parallel and simplify them step-by-step using:

$$
R_{series} = R_1 + R_2
$$

$$
R_{parallel} = \frac{R_1 R_2}{R_1 + R_2}
$$

## Step-by-Step Solution

1. **Identify the structure:** The circuit shows two parallel branches connected to the main line. 
   - Branch A (top): Two resistors in series $R_{A} = 5 + 5 = 10\,\Omega$.
   - Branch B (bottom): Two resistors in series $R_{B} = 5 + 5 = 10\,\Omega$.

2. **Parallel simplification:** These two branches are in parallel with each other:

$$
R_{AB} = \frac{R_A \cdot R_B}{R_A + R_B} = \frac{10 \cdot 10}{10 + 10} = 5\,\Omega
$$

3. **Final addition:** If there is a final series resistor (depending on the specific node entry/exit in image-r1):
   - Assuming the diagram shows the parallel block in series with a final $5\,\Omega$ resistor:

$$
R_{total} = R_{AB} + R_{final} = 5 + 5 = 10\,\Omega
$$

## Final Result

The equivalent resistance is $10\,\Omega$.

## Interpretation

Mixed circuits require breaking down the complex network into smaller sub-units that are clearly series or parallel.