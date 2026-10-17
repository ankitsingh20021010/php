Functions in PHP
Definition
A function is a reusable block of code that performs a specific task. Functions help reduce repetition and make programs easier to maintain.
Syntax
function functionName() {
    // code to execute
}
1. Function Without Parameters
<?php
function greet() {
    echo "Hello, Ankit!";
}

greet();
?>
Output:
Hello, Ankit!
2. Function With Parameters
<?php
function greetUser($name) {
    echo "Hello, " . $name;
}

greetUser("Ankit");
?>
Output:
Hello, Ankit
3. Function With a Return Value
<?php
function add($a, $b) {
    return $a + $b;
}

$result = add(10, 20);
echo $result;
?>
Output:
30
4. Default Parameter
<?php
function welcome($name = "Guest") {
    echo "Welcome, " . $name;
}

welcome();
?>
Output:
Welcome, Guest
Advantages
- Code can be reused.
- Reduces duplicate code.
- Makes programs easier to test and maintain.
- Breaks a large program into smaller parts.
Conclusion
In PHP, a function is declared using the function keyword and called by writing its name followed by parentheses.
