Question 1:
The bug was that the data type of result, is a string. So when it adds "1" and "2", which were my input numbers, it just concatenates them together as a string which is why it outputs "12".

Question 2:
I plan of fixing this by parsing the input strings num1 and num2 as a float before performing the addition operation on them. I will create variables x and y to store the parsed numbers of num1 and num2 respectively. 