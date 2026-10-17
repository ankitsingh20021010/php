Loops in PHP
Definition
A loop repeats a block of code while a condition is true or for each item in a collection. Loops reduce repeated code.
1. while Loop
Checks the condition before each iteration.
<?php
$i = 1;

while ($i <= 5) {
    echo $i . " ";
    $i++;
}
?>
Output: 1 2 3 4 5
2. do...while Loop
Runs the code at least once because the condition is checked after the loop body.
<?php
$i = 1;

do {
    echo $i . " ";
    $i++;
} while ($i <= 5);
?>
Output: 1 2 3 4 5
3. for Loop
Useful when the number of iterations is known.
<?php
for ($i = 1; $i <= 5; $i++) {
    echo $i . " ";
}
?>
Output: 1 2 3 4 5
4. foreach Loop
Used to iterate over arrays.
<?php
$fruits = ["Apple", "Mango", "Banana"];

foreach ($fruits as $fruit) {
    echo $fruit . " ";
}
?>
Output: Apple Mango Banana
Loop Control Statements
- break stops the loop immediately.
- continue skips the current iteration and moves to the next one.
<?php
for ($i = 1; $i <= 5; $i++) {
    if ($i == 3) {
        continue;
    }
    echo $i . " ";
}
?>
Output: 1 2 4 5
Conclusion
PHP provides while, do...while, for, and foreach loops. Choose a loop based on whether you need a condition-based repetition, a known number of repetitions, or array traversal.
