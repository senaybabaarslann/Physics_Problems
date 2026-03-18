1. VECTOR ALGEBRA
Problem: Given a = [2, 1, -3] and b = [4, -2, 1]
"""
# Step 1: Calculate Magnitudes using sqrt(x^2 + y^2 + z^2)
# |a| = sqrt(2^2 + 1^2 + (-3)^2) = sqrt(14) ≈ 3.74
# |b| = sqrt(4^2 + (-2)^2 + 1^2) = sqrt(21) ≈ 4.58

# Step 2: Dot Product (a . b)
# a . b = (2*4) + (1*-2) + (-3*1) = 8 - 2 - 3 = 3

# Step 3: Cross Product (a x b) using determinant
# i = (1*1) - (-3*-2) = -5
# j = ((-3)*4) - (2*1) = -14
# k = (2*-2) - (1*4) = -8
# Result: [-5, -14, -8]

# Step 4: Angle (theta)
# cos(theta) = (a.b) / (|a|*|b|) = 3 / (3.74 * 4.58) ≈ 0.175
# theta = arccos(0.175) ≈ 79.9 degrees
