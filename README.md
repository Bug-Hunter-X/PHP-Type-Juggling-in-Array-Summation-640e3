# PHP Type Juggling Bug

This repository demonstrates a common error in PHP related to type juggling. The `calculateSum` function is intended to add numbers in an array. However, due to PHP's loose typing, including a string in the array leads to unexpected behavior, as shown in `bug.php`. The solution in `bugSolution.php` addresses this issue using strict type checking.