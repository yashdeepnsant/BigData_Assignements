## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Ans: Python code is written in human readable form also in simple format (indentaion) etc.

Q2. Why is Python called a dynamically typed language?
Ans: The type of the variable is determined only during runtime, that's why we call dynamically typed language correct?

Q3. List some pros and cons of Python programming language?
Pros:
1. Beginner-Friendly 
2. Large Community
3. Flexible and Extensible
4. Extensive Libraries 
5. Embeddable
6. Highly Scalable
7. IOT Opportunities
8. Machine Learning
9. Portable
Cons:
1. Issues with Design
2. Slower than Compiled Languages
3. Security
4. Work Environment
5. Python’s Memory Consumption and Garbage Collection
6. Python is Dynamically Typed
7. Multithreading in Python

Q4. In what all domains can we use Python?
Ans: Data Engg/ AI / Machine Learning / Deep Learning etc.

Q5. What are variable and how can we declare them?
Ans: Variables are just place holder memory location for storing data values. Python has no command for declaring a variable, 
variables are created the moment you first assign a value to it.

Q6. How can we take an input from the user in Python?
Ans: name = input("Enter the Name of user")

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans: String/Char

Q8. What is type casting?
Ans: Converting value of one data type into another is called type casting.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
#Ans: No, we can't , reason the input entred by user will stored in some variable and one variable can;t store multiple values.
Ans: Yes we can, using the split function in combination with input, like:|

# taking two inputs at a time
f_e_cnt, m_e_cnt = input("Enter count of Female and Male employee count (seperated by Space): ").split()
print("Female Employee Count:",f_e_cnt)
print("Mmale Employee Count:",m_e_cnt)

Q10. What are keywords?
Ans: They are reservered words which can;t be used in programming/code as variable name etc., keywords have specific purpose and use

Q11. Can we use keywords as a variable? Support your answer with reason.
Ans: No we can;t not, Keywords have some specific purpose like, syntex rules etc.

Q12. What is indentation? What's the use of indentaion in Python?
Ans: It's just couple spaces/a tab the begining of code line, Python consider indentation to indicate a block of code.

Q13. How can we throw some output in Python?
Ans: using Print() function

Q14. What are operators in Python?
Ans: Special symbols that helps in some type of logic building/calculation etc. Ex. Arithimatic / Logical / boolean / String / Assignment etc.


Q15. What is difference between / and // operators?
Ans '/' used for float division, while '//' for integer division

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Ans: 
multi_num_str = "iNeuron"*4
print('```')
print(multi_num_str)
print('```')


Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans: 
usr_num_input = int(input("Please Enter a Number:"))
if usr_num_input%2 == 0 :
    print("The Number Entered ",usr_num_input, " is Even")
else:
    print("The Number Entered ",usr_num_input, " is Odd")

Q18. What are boolean operator?
Ans: Boolean operators are AND/OR/Not etc. which are used to evaluate an expression and retruns True or False


Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```

Ans: 
1
0
False
1
Q20. What are conditional statements in Python?
Ans: They used to evaluate some conditions in code, and accordingly take the next step

Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans: These are conditional statements, "if" used to evaluate an condition, if condition true then respective block works, if false then either of
elif or else use (if mentioned in the code), elif evaluate condition as well, program control goes to elif when "if" evaluates to false, there could
be multiple elif in the block, if none of the condition evaluates to true then "else" gets executed.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans:
input_age = int(input("Please Enter a Age:"))
if input_age >= 18 :
    print("I can vote")
else:
    print("I can't vote")


Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Ans: 
input_num1,input_num2,input_num3 = input("Enter 3 Numbers (seperated by Space): ").split()
var_max1= max(input_num1, input_num2)
var_max = max(var_max1,input_num3)
print("Max is:",var_max)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```