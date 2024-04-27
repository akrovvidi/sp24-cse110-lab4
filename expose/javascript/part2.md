## Question 1:
Line 12 in the code prints "3" because the value of variable 'i' is 3 when it gets terminated by the for loop. The value of i is made able to access even outside the for-loop since it is defined using the keyword 'var'.

## Question 2:
Line 13 in the code prints 150 since discountedPrice will store the price after discount of the last element of the prices array and we are able to access the value of 'discountedPrice' even outside the for-loop since it is defined using the 'var' keyword so it's scope is anywhere in the function. 

## Question 3:
Line 14 in the code prints 150 since finalPrice will store the discounted price of the last element of the prices array and when it applies the Math.round() to 150, it remains 150 since it is already an integer. We are able to access 'finalPrice' even outside the for-loop since it is defined using the keyword 'var' so it's scope is the entire function.

## Question 4:
This function returns the array containing all the prices after the discount has been applied to them. Nothing is outputted or printed to the console since the function simply returns the array but this is never displayed to the output. 

## Question 5:
Line 12 will cause an error. This is so because, 'i' is defined using the keyword 'let' and so its scope will only be wihtin the for-loop. Therefore, when we try to access it outisde the loop, the code causes ane error.

## Question 6:
Line 13 will cause an error. This is so because, since discountedPrice is defined using the keyword 'let' inside the for loop, it's scope will only remain inside of the for-loop and whenever we try to access 'discountedPrice' outside of the for loop, it is not defined since it is out of the scope and will therefore cause an error trying to access it.

## Question 7:
Line 14 of the code returns '150' which is the price after discount of the last price element in the prices[] array. This prints 150 although 
finalPrice is defined using 'let' since we are still accessing it in the same block it was defined in so we are in it's scope so no error caused.

## Question 8:
This function will return the discounted array. It returns the array containing the final prices of all the prices after discount. 

## Question 9:
Line 11 will cause an error since 'i' is defined using the keyword 'let'. Therefore, its scope will only be within the for-loop and when we try accessing it outside the loop, we cause an error. 

## Question 10:
Line 12 of the code will output '3' which is the length of the prices array. This is so because since length is defined using the keyword 'const', it's value cannot change and since we never try to reassign the value of 'length', there is no error caused in the code.

## Question 11:
The function will return the discounted array which contains the final prices of all the prices after discount. There will be no error even though discounted is defined using 'const' since we can still modify/alter the contents of the discounted array but can never re-assign it to a new array since it is defined as a constant. Therefore, our push operations are valid and does not cause an error.

## Question 12:
- a). student.name
- b). student['Grad Year']
- c). student.greeting()
- d). student['Favorite Teacher'].name
- e). student.courseLoad[0]

## Question 13:
- a). The output is '32' because the '+' operator concatenates strings when one operand is a string
- b). The output is 1 because the - operator converts the string '3' to a number before subtraction
- c). The output is 3 because null is treated as a zero in arithmetic operations
- d). The output is '3null' because the '+' operator concatenates strings when one operand is a string
- e). The output is 4 since true is treated as a 1 in arithmetic operations
- f). The output is 0 since both false and null are treated as zeros in arithmetic operations
- g). The output is '3undefined' because the '+' operator concatenates strings when one operand is a string
- h). The output is NaN because the '-' operator requires numeric operands and undefined cannot be converted to a number

## Question 14:
- a). The result is true because the strings are converted to numbers before they are compared
- b). The result is false due to the lexographic comparison
- c). The result is true since the '==' operator performs type coercion before the comparison
- d). The result is false since the '===' does not perform type coercion before comparison and performs strict equality comparison instead
- e). The result is false since the '==' operator does not convert boolean values to numbers before comparison
- f). The result is true since Boolean(2) evaluates to true and the '===' operator performs strict equality comparison

## Question 15:
The main difference is that '==' operator performs type coercion before the comparison. So it converts both operands to the same type before the comparison is done. On the other hand, the '===' operator does not perform type coercion and compares both value and type. 

## Question 17:
The resulting array will be [2,4,6]. For array[0], doSomething(1) returns 2.
For array[1], doSomething(2) will returns 2*2 which is 4. Finally, for array[2], doSomething(3) will return 6.

Question 19:
The output of the code is:
1
4
3
2
