# Task 02 – Resistors Combinations

## Problem Statement

You have a supply of exactly three $1\,\Omega$ resistors. What are all the possible equivalent resistances you can create by combining them? List all unique values.

## Theory

With three resistors ($R=1\,\Omega$), the following topology combinations are possible:
1. All in series.
2. All in parallel.
3. Two in series, then in parallel with the third.
4. Two in parallel, then in series with the third.

## Step-by-Step Solution

1. **All in Series:**

$$
R_{eq} = R + R + R = 3\,\Omega
$$

2. **All in Parallel:**

$$
\frac{1}{R_{eq}} = \frac{1}{R} + \frac{1}{R} + \frac{1}{R} \implies R_{eq} = \frac{1}{3}\,\Omega \approx 0.33\,\Omega
$$

3. **Two in Series, Parallel with Third:**
First, $R_s = R + R = 2\,\Omega$. Then parallel:

$$
R_{eq} = \left( \frac{1}{2} + \frac{1}{1} \right)^{-1} = \left( \frac{3}{2} \right)^{-1} = \frac{2}{3}\,\Omega \approx 0.67\,\Omega
$$

4. **Two in Parallel, Series with Third:**
First, $R_p = \left( \frac{1}{1} + \frac{1}{1} \right)^{-1} = 0.5\,\Omega$. Then series:

$$
R_{eq} = 0.5\,\Omega + 1\,\Omega = 1.5\,\Omega
$$

## Final Result

The unique possible equivalent resistances are:
$0.33\,\Omega$, $0.67\,\Omega$, $1.5\,\Omega$, and $3\,\Omega$.

## Interpretation

By changing the topology of the connections, we can achieve values both higher and lower than the individual component values, as well as fractional values of the base resistance.