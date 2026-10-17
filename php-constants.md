Constants in PHP
Definition
A constant is a named value that cannot be changed after it has been defined. Constants are useful for values that should remain fixed throughout a program.
1. Using define()
<?php
define("SITE_NAME", "My PHP Website");
echo SITE_NAME;
?>
Output:
My PHP Website
2. Using const
<?php
const PI = 3.14159;
echo PI;
?>
Output:
3.14159
Rules for Constants
- A constant does not use $ before its name.
- A constant is accessed by its name.
- Once defined, its value cannot be reassigned.
- Constant names are conventionally written in uppercase.
- define() is executed at runtime; const is generally declared at compile time and has some context restrictions.
Constant vs Variable
Constant	Variable
No $ symbol	Starts with $
Value cannot be reassigned	Value can be changed
Example: SITE_NAME	Example: $name


Example
<?php
define("COLLEGE", "BBD University");
const YEAR = 2026;

echo COLLEGE;
echo YEAR;
?>
Conclusion
PHP constants store fixed values. They can be created with define() or the const keyword.
