1) It prints
```3```
because the counter variable `i` is declared with `var`, so it is still accessible outside the for loop. Because there are 3 elements in the `prices` array, it prints `3`.

2) It prints
```150```
because `discountedPrice` is declared with `var`, so it can be accessed outside the for loop. It retains the final value that it is set to, so it will contain the `0.5` discounted price for `300`, which is `150`.

3) It prints
```150```
The final iteration of the for loop sets `finalPrice` to `discountedPrice` rounded to the hundredths place.

4) The function returns the array
```[ 50, 100, 150 ]```
The discount of `0.5` is applied to each element in the array `prices` and is returned as a new array.

5) It throws an error because `i` is declared with `let`, so it cannot be accessed outside the for loop.

6) It throws an error because `discountedPrice` is declared with `let`, so it cannot be accessed outside the for loop.

7) It prints
```150```
The final iteration of the for loop sets `finalPrice` to `discountedPrice` rounded to the hundredths place.

8) The function returns the array
```[ 50, 100, 150 ]```
The `let` keyword does not change the answer from question 4.

9) It throws an error because `i` is declared with `let`, so it cannot be accessed outside the for loop.

10) It prints
```3```
`length` is just set to the number of prices passed in and is never reassigned.

11) The function returns the array
```[ 50, 100, 150 ]```
The discount of `0.5` is applied to each element in the array `prices` and is returned as a new array. None of the rules for `const` or `let` are violated, so no errors occur.

12) - A. `student.name`
    - B. `student['Grad Year']`
    - C. `student.greeting()`
    - D. `student['Favorite Teacher'].name`
    - E. `student.courseLoad[0]`

13) - A. `'32'`, the `2` was converted into a string for concatenation
    - B. `1`, the `'3'` was converted to an integer for subtraction
    - C. `'3'`, the `null` was converted to `0` for addition
    - D. `'3null'`, the `null` was converted to a string for concatenation
    - E. `4`, the `true` was converted to `1` for addition
    - F. `0`, the `false` and `null` were both converted to `0` for addition
    - G. `'3undefined'`, the `undefined` was converted to a string for concatenation
    - H. `NaN`, the `'3'` was converted to an integer for subtraction, but subtracting `undefined` returned `NaN`

14) - A. `true`, the `'2'` gets converted to an integer for comparison
    - B. `false`, string comparison uses lexigraphical ordering
    - C. `true`, the `'2'` gets converted to an integer for comparison
    - D. `false`, the `'2'` is not converted to an integer, so they are not the same
    - E. `false`, the `true` gets converted to a `1`, which is not equal to `2`
    - F. `true`, the `Boolean(2)` evaluates to `true`

15) `==` allows for type conversion during comparison. `===` does not do any type conversion.

16) *another file*

17) `[ 2, 4, 6 ]`. The `doSomething` function returns twice the number passed in. The `modifyArray` function therefore doubles each value in `array` and stores that in a new array.

18) *another file*

19) ```
    1
    4
    3
    2
    ```