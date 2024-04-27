Question 1:
Line 9 in the code prints the following: "values added: 20". This is so because
result is declared using the 'var' keyword and stores the result of adding num1 and num2 which is 10+10 which equals 20.

Question 2:
Line 13 in the code prints the following: "final result: 20". 

Question 3:
Line 9 in the code prints the following: "values added:  20".

Question 4:
Line 13 in the code returns an error. This is so because, result is defined using the 'let' keyword and therefore it's scope is only the if block and if it is accessed anywhere outside the block, the code will throw an error since it is out of the scope. 

Question 5:
Line 9 in the code returns an error. This is so because result is defined using the 'const' keyword which defines result as a constant so it's value cannot be changed. Therefore, when we try to re-assign the value of result to equal to the result of adding num1 and num2, the code throws an error since the value of a constant cannot be changed. 

Question 6:
Line 13 in the code does not even execute because there was an error in Line 9 which tried to re-assign a value to a constant variable.