1. The output will be 3 because i is declared with var, which has function scope, and thus its value can be accessed after the for-loop concludes.

2. The output will be 150 as discountedPrice is a var with function scope, so the final value calculated in the for-loop (line 7) is available outside of the loop.

3. The output will be 150 since finalPrice is a var with function scope, allowing access to the last calculated value (line 8) throughout the function.

4. The function returns an array [50, 100, 150] because the return value discounted is a var with function scope, so it's available throughout the code. In the for-loop, valid values are added to the discounted array, each being half of the corresponding input value.

5. Error - i is not accessible outside the for-loop because it is declared with let, which limits its scope to within the for-loop block.

6. Error - discountedPrice is not accessible outside the for-loop because it is declared with let, limiting its scope to within the for-loop block.

7. The output will be 150 since finalPrice is declared with let and has block scope within the entire function. The last calculated value (line 8) is available throughout the function.

8. The function returns an array [50, 100, 150] because the return value discounted has let block scope within the entire function. In the for-loop, valid values are added to the discounted array, each being half of the corresponding input value.

9. Error - i is not accessible outside the for-loop because it is declared with let, limiting its scope to within the for-loop block.

10. The output will be 3 because the const variable length has block scope for the entire function, making it available throughout the code.

11. The function returns an array [50, 100, 150] because the return value discounted has const block scope within the entire function. In the for-loop, valid values are added to the discounted array, each being half of the corresponding input value. Although discounted is a constant reference to an array, its elements can be reassigned, allowing new elements to be added.

12.
A: student.name
B: student['Grad Year']
C: student.greeting()
D: student['Favorite Teacher'].name
E: student.courseLoad[0]

13. A: '32', since '2' is converted to a string and concatenated.
B: 1, since '3' is converted to a number and then subtraction is performed.
C: 3, since null is converted to 0 and added to 3.
D: '3null', since null is converted to a string and concatenated.
E: 4, since true is converted to 1 and added to 3.
F: 0, since both false and null are converted to 0 and added together.
G: '3undefined', since undefined is converted to a string and concatenated.
H: NaN, since '3' is converted to a number, but undefined cannot be converted for subtraction, resulting in NaN.

14.
A: true, because the string '2' is coerced into the number 2 for the comparison.
B: false, because when comparing strings, lexicographic order is used, and in this case, '12' comes before '2'.
C: true, because the string '2' is coerced into the number 2 for the comparison.
D: false, because the === operator checks for both value and type equality, and the types (number and string) are different.
E: false, because the boolean value true is coerced into the number 1 for the comparison, and 1 is not equal to 2.
F: true, because the Boolean(2) evaluates to true, and true === true returns true.

15.
The difference between == and === is that the == operator performs type coercion before comparing values, while the === operator requires both the value and the type to be equal without any type coercion.

17.
The function returns the array [2, 4, 6]. The modifyArray function iterates over each element of the input array, applies the callback function (doSomething), which doubles the input value, and then pushes the resulting value into the new array. The new array is returned after all elements have been processed.

19.
The console output is:
```
1
4
3
2
```
