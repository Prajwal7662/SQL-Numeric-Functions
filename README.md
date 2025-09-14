📌Numeric Functions in SQL
Introduction

Numeric functions in SQL are built-in functions that perform mathematical operations on numeric data types. These functions are widely used in queries for calculations, data analysis, and reporting. They help in manipulating numeric values without writing complex manual logic.

Commonly Used Numeric Functions

ABS(n)

Returns the absolute (positive) value of a number.

Example: ABS(-25) → 25.

CEIL(n) / CEILING(n)

Returns the smallest integer greater than or equal to the given number.

Example: CEIL(4.2) → 5.

FLOOR(n)

Returns the largest integer less than or equal to the given number.

Example: FLOOR(4.8) → 4.

ROUND(n, d)

Rounds a number to a specified number of decimal places.

Example: ROUND(123.456, 2) → 123.46.

TRUNC(n, d)

Truncates a number to a specified number of decimal places without rounding.

Example: TRUNC(123.456, 2) → 123.45.

MOD(a, b)

Returns the remainder after dividing a by b.

Example: MOD(10, 3) → 1.

POWER(a, b)

Returns a raised to the power of b.

Example: POWER(2, 3) → 8.

SQRT(n)

Returns the square root of a number.

Example: SQRT(16) → 4.

EXP(n)

Returns the exponential value of n (e^n).

Example: EXP(1) → 2.718....

LOG(n)

Returns the natural logarithm (base e) of a number.

Example: LOG(10) → 2.302....

LOG10(n)

Returns the logarithm base 10 of a number.

Example: LOG10(100) → 2.

SIGN(n)

Returns the sign of a number: -1 (negative), 0 (zero), 1 (positive).

Example: SIGN(-50) → -1.

PI()

Returns the value of pi.

Example: PI() → 3.14159....

RAND()

Returns a random floating-point value between 0 and 1.

Example: RAND() → 0.726....

DEGREES(n)

Converts radians to degrees.

Example: DEGREES(PI()) → 180.

RADIANS(n)

Converts degrees to radians.

Example: RADIANS(180) → 3.14159....

Use Cases

Performing mathematical calculations in queries.

Data transformation for analytics and reporting.

Rounding off values for presentation.

Generating random test data.

Statistical and financial analysis.

Conclusion

Numeric functions in SQL simplify handling of numeric values by providing ready-to-use mathematical operations. They are essential for data manipulation, reporting, and decision-making in database systems.
