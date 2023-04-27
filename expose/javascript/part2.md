1. What will happen at line 12 and why? If the code causes an error, explain why.

At line 12, `3` will be printed because of the command `console.log(i)`. The variable `i` is declared in the for loop using the keyword `var`, which means that it can be accessed anywhere in the function. The variable `i` is updated in the for loop until does not satisfy this condition `i < prices.length`. As can be seen by the list that we give the function, `prices = [100, 200, 300]`, which means that it has a length of `3`. Thus, after the for loop runs, the last value of `i = 3`, which is why line 12 will print `3`.

2. What will happen at line 13 and why? If the code causes an error, explain why.

At line 13, `150` will be printed because the `console.log()` is instructed to print `discountedPrice`. On line 7, `discountedPrice` is declared as a `var` and is constantly updated in the for loop. In the last round of the for loop, it is updated to be `prices[i] * (1 - discount)`. In the last round of the for loop, `i = 2`. Thus, when we do the math we get `prices[2] * (1 - discount) = 300 * (1 - 0.5) = 300 * 0.5 = 150`.

3. What will happen at line 14 and why? If the code causes an error, explain why.

At line 14, the value `150` will be printed because `console.log()` wants to print the value of `finalPrice`. In the for loop, we can see that `finalPrice` is constantly updated when the for loop runs. The last time `finalPrice` is updated, `discountedPrice` had the value `150`, which was explained in the previous step. Then, we want to calculate `finalPrice = Math.round(discountedPrice * 100) / 100 = Math.round(150 * 100) / 100 = 15000/100 = 150`. As a result, when `finalPrice` is printed after the for loop ends, the value printed is `150`.

4. What will this function return? Give a brief explanation why. If the code causes an error, explain why.

The function will return the array of discounted prices in the following format `[50, 100, 150]`. Inside the function, we initialized an empty array called `discounted`. In the for loop, we will iterate through the given array `prices` and calculate the new discounted price of each element in `prices` using the given `discount`. Each time the `finalPrice` is calculate, we push that new discounted price into the array `discounted`. Since the for loop runs through every element in the given `prices` array, `discounted` will have the same amount of elements, but the values will be the discounted version of the original values.

5. What will happen at line 12 and why? If the code causes an error, explain why.

The code will cause an error because line 12 is trying to print the value of `i`. However, `i` was declared using the `let` keyword, which means that it is only accessible in the scope that it was placed in. In other words, `i` is only accessible in the for loop and not outside. Meanwhile, the `console.log()` command is outside the for loop, so it is unable to access `i`, causing an error.

6. What will happen at line 13 and why? If the code causes an error, explain why.

The code will cause an error because line 13 is trying to print the value of `discountedPrice`. However, `discountedPrice` was declared using the `let` keyword, so it is only accessible in the for loop and not outside. The `console.log()` command is outside the for loop, so it is unable to access `discountedPrice`, causing an error.

7. What will happen at line 14 and why? If the code causes an error, explain why.

At line 14, the value `150` will be printed because `console.log()` wants to print the value of `finalPrice`. Since `console.log()` is in the same scope as `finalPrice`, which was declared using `let`, there is no error when trying to access the value of `finalPrice`. As for the value that is printed, `finalPrice` will be updated every time the for loop runs. In the last round of the for loop, `finalPrice = Math.round(discountedPrice * 100) / 100 = Math.round(150 * 100) / 100 = 150` like in question 3.

8. What will this function return? Give a brief explanation. If the code causes an error, explain why.

The function will return the array `discounted` which is `[50, 100, 150]`. While the array `discounted` was declared using the keyword `let`, the statement `return discounted` is still within the same scope, so there are no errors when running the function. As for the array, the discounted values of the given array `prices` are pushed into the empty array `discounted` in the for loop, which is like question 4.

9.  What will happen at line 11 and why? If the code causes an error, explain why.

The code will cause an error because line 11 is trying to print the value of `i`. However, `i` was declared using the `let` keyword, thus it is only accessible in the for loop. Since the `console.log()` command is outside the for loop, `i` cannot be found and the code causes an error.

10. What will happen at line 12 and why? If the code causes an error, explain why.

At line 12, the value of `length` will be printed, which is `3`. Since `length` was set to the value of `prices.length` and the length of the given array `[100, 200, 300]` is `3`, `length = 3`. Additionally, since the `console.log()` call is in the same scope as the declaration of `length`, there are no errors and `length` can be accessed.

11.  What will this function return? Give a brief explanation. If the code causes an error, explain why.

The function will return the array `[50, 100, 150]`. Even though the array `discounted` was declared using `const` and initialized to an array, as long as the array is not replaced with a new array, there will be no errors. As for the values, in the for loop, discounted prices will be calculated for every element in the original array and added to the array `discounted`. Then, `discounted` will be returned.

12. Given the above Object, write the notation for:
    
    A. Accessing the value of the name property in the student object

    `student.name`

    B. Accessing the value of the Grad Year property in the student object

    `student['Grad Year']`

    C. Calling the function for the greeting property in the student object

    `student.greeting()`

    D. Accessing the name property of the object in the Favorite Teacher property in student

    `student['Favorite Teacher'].name`

    E. Access index zero in the array of the courseLoad property of the student object

    `student.courseLoad[0]`

  