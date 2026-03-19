# ==========================================================
# QUESTION 1: VECTOR ALGEBRA - DETAILED STEP-BY-STEP SOLUTION
# ==========================================================

# Given Vectors:
# a = [2, 1, -3]
# b = [4, -2, 1]

# ----------------------------------------------------------
# a) Magnitude of Vector a (|a|)
# ----------------------------------------------------------
# Step 1: Write down the 3D Magnitude formula: |v| = sqrt(x^2 + y^2 + z^2)
# Step 2: Plug in the components of vector a:
#         |a| = sqrt( (2)^2 + (1)^2 + (-3)^2 )
# Step 3: Calculate the squares:
#         |a| = sqrt(4 + 1 + 9)
# Step 4: Sum the values and find the square root:
#         |a| = sqrt(14) ≈ 3.74

# ----------------------------------------------------------
# b) Magnitude of Vector b (|b|)
# ----------------------------------------------------------
# Step 1: Use the same formula for vector b:
#         |b| = sqrt( (4)^2 + (-2)^2 + (1)^2 )
# Step 2: Calculate the squares (Note: negative squared becomes positive):
#         |b| = sqrt(16 + 4 + 1)
# Step 3: Final Calculation:
#         |b| = sqrt(21) ≈ 4.58

# ----------------------------------------------------------
# c) Dot Product (a . b)
# ----------------------------------------------------------
# Step 1: Formula: (ax * bx) + (ay * by) + (az * bz)
# Step 2: Multiply corresponding components:
#         x: (2 * 4) = 8
#         y: (1 * -2) = -2
#         z: (-3 * 1) = -3
# Step 3: Sum the results:
#         8 + (-2) + (-3) = 8 - 5 = 3
# Result: The Dot Product is a scalar value of 3.

# ----------------------------------------------------------
# d) Cross Product (a x b)
# ----------------------------------------------------------
# Step 1: Set up the determinant matrix with i, j, k unit vectors.
#         | i   j   k |
#         | 2   1  -3 |
#         | 4  -2   1 |
# Step 2: Calculate the 'i' component (hide row 1, col 1):
#         i * [(1 * 1) - (-3 * -2)] = i * [1 - 6] = -5i
# Step 3: Calculate the 'j' component (hide row 1, col 2 and use MINUS sign):
#         -j * [(2 * 1) - (-3 * 4)] = -j * [2 - (-12)] = -j * [14] = -14j
# Step 4: Calculate the 'k' component (hide row 1, col 3):
#         k * [(2 * -2) - (1 * 4)] = k * [-4 - 4] = -8k
# Final Vector: [-5, -14, -8]

# ----------------------------------------------------------
# e) Angle Calculation (theta)
# ----------------------------------------------------------
# Step 1: Formula: cos(theta) = (a . b) / (|a| * |b|)
# Step 2: Substitute the values we found above:
#         cos(theta) = 3 / (sqrt(14) * sqrt(21))
# Step 3: Calculate the denominator:
#         sqrt(14) * sqrt(21) = sqrt(294) ≈ 17.146
# Step 4: Find the ratio:
#         cos(theta) = 3 / 17.146 ≈ 0.175
# Step 5: Calculate the inverse cosine (arccos) to find theta:
#         theta = arccos(0.175)
# Result: theta ≈ 79.9 degrees (or approx 1.39 radians)
