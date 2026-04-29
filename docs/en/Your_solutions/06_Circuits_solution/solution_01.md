# Task 01 – Series and Parallel Circuits

## Problem Statement

You have three resistors, $R_1=15\,\Omega$, $R_2=30\,\Omega$, and $R_3=50\,\Omega$ and a $12\,\text{V}$ battery. Calculate the total equivalent resistance and the current flowing from the battery for two cases:
1. All resistors connected in series.
2. All resistors connected in parallel.

## Theory

For resistors in series, the equivalent resistance $R_{eq}$ is the sum of individual resistances:

$$
R_{eq} = \sum_{i=1}^{n} R_i = R_1 + R_2 + \dots + R_n
$$

For resistors in parallel, the reciprocal of the equivalent resistance is the sum of the reciprocals:

$$
\frac{1}{R_{eq}} = \sum_{i=1}^{n} \frac{1}{R_i} = \frac{1}{R_1} + \frac{1}{R_2} + \dots + \frac{1}{R_n}
$$

The current $I$ drawn from the battery is determined by Ohm's Law:

$$
I = \frac{V}{R_{eq}}
$$

## Step-by-Step Solution

### Case 1: Series Connection

1. Calculate total resistance:

$$
R_{eq,s} = 15\,\Omega + 30\,\Omega + 50\,\Omega = 95\,\Omega
$$

2. Calculate total current:

$$
I_s = \frac{12\,\text{V}}{95\,\Omega} \approx 0.1263\,\text{A}
$$

### Case 2: Parallel Connection

1. Calculate total resistance:

$$
\frac{1}{R_{eq,p}} = \frac{1}{15} + \frac{1}{30} + \frac{1}{50}
$$

$$
\frac{1}{R_{eq,p}} = \frac{10}{150} + \frac{5}{150} + \frac{3}{150} = \frac{18}{150}
$$

$$
R_{eq,p} = \frac{150}{18} \approx 8.33\,\Omega
$$

2. Calculate total current:

$$
I_p = \frac{12\,\text{V}}{8.33\,\Omega} = 1.44\,\text{A}
$$

## Final Result

- **Series:** $R_{eq} = 95\,\Omega$, $I = 0.126\,\text{A}$
- **Parallel:** $R_{eq} = 8.33\,\Omega$, $I = 1.44\,\text{A}$

## Interpretation

In a series circuit, the total resistance is always greater than the largest individual resistor, resulting in a lower current. In a parallel circuit, the equivalent resistance is smaller than the smallest individual resistor, leading to a significantly higher current draw from the same voltage source.