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
Ans:
numbers = [12, 75, 150, 180, 145, 525, 50]
var_sum = 0
for num in numbers:
    if num%2 == 0:
        var_sum=var_sum+num

print("The sum of even numbers is:", var_sum)


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
Ans: 
numbers = [12, 75, 150, 180, 145, 525, 50]
for num in numbers:
    if num > 500:
        break
    elif num > 150:
        continue
    elif num%5 == 0:
        print(num)

Q26. What is a string? How can we declare string in Python?
Ans: string are nothing but array of one or more characters, we can declar string like : str_var = "Hello iNeuron"

Q27. How can we access the string using its index?
Ans: print(str[0:2])

Q28. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "iNeuron"

Ans: 

Option : 1
str = "Big Data iNeuron"

 op_str=''
 for i in range(9,len(str)):
     print(str[i])
     op_str=op_str+str[i]
 print(op_str)

Option : 2
print(str[9:]) # Ans for 28


Q29. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "norueNi"

Ans: print(str[:8:-1])


Q30. Resverse the string given in the above question.

Ans : print(str[::-1])

Q31. How can you delete entire string at once?
Ans: del(str)


Q32. What is escape sequence?
Ans: if we would like to put " or ' quotes or special chars in the string, mean part of the string, for that we use escape sequence, "\" is used
for that purpose.
ex: string = "Big Data \"iNeuron\""

Q33. How can you print the below string?

'iNeuron's Big Data Course'
print("\'iNeuron\'s Big Data Course\'")

Q34. What is a list in Python?
Ans: list is a collection of things/elements, enclosed in [ ] and separated by commas. It's a sequence data type

Q35. How can you create a list in Python?
Ans: list_var=[1,2,3,4], list_str_var =['Hi',"Hello","How are you"]

Q36. How can we access the elements in a list?
Ans: As lists are sequence data type, we can access elements by the index position
list_str_var =['Hi','Hello','How are you']
print(lst[1])
o/p: Hello

Q37. Write a code to access the word "iNeuron" from the given list.

lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]

Ans: 
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
print(lst[4][2]) # Ans for 37

Q38. Take a list as an input from the user and find the length of the list.
Ans: 
List_of_char = list((input("Enter the List of string:")))
print(List_of_char)
print("Length of List is: ",len(List_of_char))	


Q39. Add the word "Big" in the 3rd index of the given list.

lst = ["Welcome", "to", "Data", "course"]

Ans: 
lst = ["Welcome", "to", "Data", "course"]
print(lst)
lst[2]="Big"+lst[2]
print(lst)

Q40. What is a tuple? How is it different from list?
Ans: Tuple is another sequence datatype like list, however tuples are immutable, i.e. we can change the values in tuples, list are mutable.
Also, when we defin them we use round brackets () instead of square brackets[] used for lists


Q41. How can you create a tuple in Python?
Ans: tup_var=() -- empty
tup_var=(10,20,30,40)


Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.
Ans: tup_str=("My","name","is")
tup_str[3] ="Rajesh" --- this is not supported, reason being tuples are immutable we can't change them.

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
Ans: There is no direct function to appended tuple with another one, however as we can concat two tuples so that option can be use.
Not sure if thats the right way.
tup_a_var =(1,2,3)
tup_b_var =(4,5,6)
tup_res_var = tup_a_var + tup_b_var
print(tup_res_var)


Q44. Take a tuple as an input and print the count of elements in it.
Ans:
tup_var = tuple((input("Enter the string:")))
print(tup_var)
print("Length of Tuple is: ",len(tup_var))

Q45. What are sets in Python?
Ans: Set is another sequence data tyep, an unordered collection of data types that are iterable, mutable and has no duplicate elements.

Q46. How can you create a set?
Ans: 
set2 ={'monday','tuesday'}
print(set2)
print(type(set2))

Q47. Create a set and add "iNeuron" in your set.
Ans: 
set2 ={'Big','Data'}
print(set2)
set2.add("iNeuron")
print(set2)

Q48. Try to add multiple values using add() function.
Ans: 
set2 ={'Big','Data'}
print(set2)
set2.add("iNeuron")
set2.add("Learning")
set2.add("is")
set2.add("good so far")
print(set2)


Q49. How is update() different from add()?
Ans: update helps us to allow us to add 2 or more elements, it accepts list, tuple etc., add() can add only 1 element at time.

Q50. What is clear() in sets?
Ans: 
set2 ={'Big','Data'}
print(set2)
set2.clear()
print(set2)

Q51. What is frozen set?
Ans: Frozen sets in Python are immutable objects that only support methods and operators that produce a result without affecting 
the frozen set or sets to which they are applied.

Q52. How is frozen set different from set?
Ans: Frozen Sets are immutable while set are mutable.

Q53. What is union() in sets? Explain via code.
Ans:
set_a ={1,2,3,4,5,6}
set_b ={3,6,8,9,10}

op_set = set_a.union(set_b)
print(op_set)

Another option:

print(set_a | set_b)

Q54. What is intersection() in sets? Explain via code.
Ans: 
set_a ={1,2,3,4,5,6}
set_b ={3,6,8,9,10}

op_set = set_a.intersection(set_b)
print(op_set)

Aother Option: print(set_a & set_b)


Q55. What is dictionary in Python?
Ans: dictionary is a collection of keys value pairs. Key-Value make it more optimized.

Q56. How is dictionary different from all other data structures.
Ans: Dictionary collection of keys values, used to store data values like a map, which, unlike other data types which hold only a single value as an element.

Q57. How can we delare a dictionary in Python?
Ans: dict1={}
print(type(dict1))

Q58. What will the output of the following?

var = {}
print(type(var))

<class 'dict'>

Q59. How can we add an element in a dictionary?

Ans: 
dict2 ={}
dict2['name']="Anshul"
dict2['age']="33"
dict2['skills']=["Python",'Java']


Q60. Create a dictionary and access all the values in that dictionary.
Ans: 
dict2 ={}
dict2['name']="Anshul"
dict2['age']="33"
dict2['skills']=["Python",'Java']
all_values= list(dict2.values())
print("All values:", all_values)


Q61. Create a nested dictionary and access all the element in the inner dictionary.
Ans:
Dict = {'dicta': {1: 'Big Data'},
        'dictb': {2: 'Learning'}}
  
# Accessing element using key
print(Dict['dicta'])
print(Dict['dicta'][1])
print(Dict['dictb'][2])


Q62. What is the use of get() function?
Ans: return the value for the given key if present in the dictionary

Q63. What is the use of items() function?
Ans:  items() method is used to return the list with all dictionary keys with values

Q64. What is the use of pop() function?
Ans: delete/removes and returns the specified element from the dictionary based on the key

Q65. What is the use of popitems() function?
Ans: removes the last inserted key-value pair from the dictionary and returns it as a tuple

Q66. What is the use of keys() function?
Ans: This gives list of all the keys in the dictionary in order of insertion

Q67. What is the use of values() function?
Ans: Returns all the values of the dictionary (as a list datatype)

Q68. What are loops in Python?
Ans: Loops are used to manage any type of looping requirements where we have iterate based on conditions/logic

Q69. How many type of loop are there in Python?
Ans: While and For Loop, on need basis we can use then as nested loop

Q70. What is the difference between for and while loops?
Ans: For Loop have definative condition, WHILE does not

Q71. What is the use of continue statement?
Ans: Skipping the execution for a certain condition while processing in loop, it just skip the code written after continue keyword, and control is 
back to begining of loop

Q72. What is the use of break statement?
Ans: To stop the execution for loop and contol is out of loop

Q73. What is the use of pass statement?
Ans: use to write empty loops

Q74. What is the use of range() function?
Ans: used to iterate a certain number of times in "for" loops

Q75. How can you loop over a dictionary?
Ans: There are multiple ways to iterate over a dictionary in Python.

Access key using the build .keys() 
Access key without using a key() 
Iterate through all values using .values()
Iterate through all key, and value pairs using items()
Access both key and value without using items()
Print items in Key-Value in pair 


Coding problems
Q76. Write a Python program to find the factorial of a given number.
Ans: 
def factorial(n):
    return 1 if (n==1 or n==0) else n * factorial(n - 1);
num = 10;
print("Factorial of",num,"is",factorial(num))

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (PRT)/100
Ans: 
def simple_interest(p,t,r):
    print('The principal is', p)
    print('The time period is', t)
    print('The rate of interest is',r)
     
    si = (p * t * r)/100
     
    print('The Simple Interest is', si)
    return si

simple_interest(8, 6, 8)

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.
Ans:
def compound_interest(principle, rate, time):

	Amount = principle * (pow((1 + rate / 100), time))
	CI = Amount - principle
	print("Compound interest is", CI)
compound_interest(10000, 10.25, 5)


Q79. Write a Python program to check if a number is prime or not.
Ans:
num = 100
if num > 1:
    # Iterate from 2 to n / 2
    for i in range(2, int(num/2)+1):
        # If num is divisible by any number between 2 and n / 2, it is not prime
        if (num % i) == 0:
            print(num, "is not a prime number")
            break
    else:
        print(num, "is a prime number")
else:
    print(num, "is not a prime number")

Q80. Write a Python program to check Armstrong Number.
Ans:
n = 10
s = n # assigning input value to the s variable
b = len(str(n))
sum1 = 0
while n != 0:
	r = n % 10
	sum1 = sum1+(r**b)
	n = n//10
if s == sum1:
	print("The given number", s, "is armstrong number")
else:
	print("The given number", s, "is not armstrong number")

Q81. Write a Python program to find the n-th Fibonacci Number.
Ans: 
def fibonacci(n):
    a = 0
    b = 1
     
    if n == 0:
        return 0
    elif n == 1:
        return b
    else:
        for i in range(1, n):
            c = a + b
            a = b
            b = c
        return b
print(fibonacci(10))

Q82. Write a Python program to interchange the first and last element in a list.
Ans: 
def swapele_list(list, pos1, pos2):
     
    list[pos1], list[pos2] = list[pos2], list[pos1]
    return list
 
List = [1, 3, 4, 2]
pos1, pos2  = 1, 3
 
print(swapele_list(List, pos1, pos2))

Q83. Write a Python program to swap two elements in a list.
Ans:
def swapPositions(list, pos1, pos2):
     
    # popping both the elements from list
    first_ele = list.pop(pos1)  
    second_ele = list.pop(pos2-1)
    
    # inserting in each others positions
    list.insert(pos1, second_ele) 
    list.insert(pos2, first_ele) 
     
    return list
 
# Driver function
List = [23, 65, 19, 90]
pos1, pos2  = 1, 3

print(List)
print(swapPositions(List, pos1-1, pos2-1))

Q84. Write a Python program to find N largest element from a list.

Q85. Write a Python program to find cumulative sum of a list.

Q86. Write a Python program to check if a string is palindrome or not.

Q87. Write a Python program to remove i'th element from a string.

Q88. Write a Python program to check if a substring is present in a given string.

Q89. Write a Python program to find words which are greater than given length k.

Q90. Write a Python program to extract unquire dictionary values.

Q91. Write a Python program to merge two dictionary.

Q92. Write a Python program to convert a list of tuples into dictionary.

Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.

Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
Q94. Write a Python program to get all combinations of 2 tuples.

Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
Q95. Write a Python program to sort a list of tuples by second item.

Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
Q96. Write a python program to print below pattern.

* 
* * 
* * * 
* * * * 
* * * * * 
Q97. Write a python program to print below pattern.

    *
   **
  ***
 ****
*****
Q98. Write a python program to print below pattern.

    * 
   * * 
  * * * 
 * * * * 
* * * * * 
Q99. Write a python program to print below pattern.

1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
Q100. Write a python program to print below pattern.

A 
B B 
C C C 
D D D D 
E E E E E 