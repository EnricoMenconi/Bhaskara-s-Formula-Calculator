Bhaskara's Formula Calculator

This is a Python-based calculator that solves quadratic equations by applying Bhaskara's formula. The program calculates the roots of quadratic equations in the form:

ax² + bx + c = 0

The coefficients a, b, and c, provided by the user, can be positive, negative, integers, or decimal numbers. The roots are calculated using the formula:

x = (-b ± √Δ) / 2a

Where Δ is given by the formula:

Δ = b² - 4ac

Features:

•	Handles cases where Δ > 0, Δ = 0, and Δ < 0 to determine if there are two distinct real roots, one real root, or no real solutions.
•	Ensures that the coefficient a cannot be zero, as this would not be a quadratic equation.
•	Provides clear output for the calculated value of Δ (delta) and the solutions to the equation if they exist.

Notes:

•	The program ensures that the value of a is not zero, which would result in a linear equation instead of a quadratic one.
•	If the value of Δ is negative, the program informs the user that there are no real solutions.

