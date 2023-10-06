# SQLquestion31
The difference between NVL and NVL2 functions?


These functions work with any data type and pertain to the use of null values in the expression list. These are all single-row functions i.e. provide one result per row.

NVL(expr1, expr2): In SQL, NVL() converts a null value to an actual value. Data types that can be used are date, character, and number. Data types must match with each other. i.e. expr1 and expr2 must be of the same data type.
 

Syntax:

NVL (expr1, expr2)
NVL2(expr1, expr2, expr3):  The NVL2 function examines the first expression. If the first expression is not null, then the NVL2 function returns the second expression. If the first expression is null, then the third expression is returned i.e. If expr1 is not null, NVL2 returns expr2. If expr1 is null, NVL2 returns expr3. The argument expr1 can have any data type.

Syntax:

NVL2 (expr1, expr2, expr3)
