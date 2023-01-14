## Assignment Part-2 python mega assignment
<!-- Q1. Why do we call Python as a general purpose and high-level programming language? -->

<!-- Q2. Why is Python called a dynamically typed language?

Q3. List some pros and cons of Python programming language?

Q4. In what all domains can we use Python?

Q5. What are variable and how can we declare them?

Q6. How can we take an input from the user in Python?

Q7. What is the default datatype of the value that has been taken as an input using input() function?

Q8. What is type casting?

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Q10. What are keywords?

Q11. Can we use keywords as a variable? Support your answer with reason.

Q12. What is indentation? What's the use of indentaion in Python?

Q13. How can we throw some output in Python?

Q14. What are operators in Python?

Q15. What is difference between / and // operators?

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Q18. What are boolean operator?

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```

Q20. What are conditional statements in Python?

Q21. What is use of 'if', 'elif' and 'else' keywords?

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50] -->

Q26. What is a string? How can we declare string in Python?
A26. A string is a sequence of characters. 
```python
str1 = "hello"

```

Q27. How can we access the string using its index?
A26.
```python
str="Winter"
print(str[0:6])
```
Q28. Write a code to get the desired output of the following
A28.
```python

string = "Big Data iNeuron"
print(string[-7::1])
desired_output = "iNeuron"

```

Q29. Write a code to get the desired output of the following
A29.
```python
string = "Big Data iNeuron"
print(string[-1:-8:-1])
desired_output = "norueNi"
```

Q30. Resverse the string given in the above question.
A30.
```python
string="Big Data iNeuron"
print(string[::-1])
```
Q31. How can you delete entire string at once?
A31.
```python
str1="string"
del str1
```

Q32. What is escape sequence?
A32. An escape sequence is a sequence of characters that, when used inside a character or string, does not represent itself but is converted into another character or series of characters that may be difficult or impossible to express directly, like newline (\n), tab (\t), and so on.

Q33. How can you print the below string?
```
'iNeuron's Big Data Course'
```
A33. 
```python
print("'iNeuron's Big Data Course'")
```

Q34. What is a list in Python?
A34. A list is a collection of similar or different types of data. A list is created in Python by placing items inside [], separated by commas.

Q35. How can you create a list in Python?
A35. One can create a list by opening and closing the square brackets.


Q36. How can we access the elements in a list?
A36. We can access the elements in a list by indexing

Q37. Write a code to access the word "iNeuron" from the given list.
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
``` 
A37.
```python
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
print(lst[4][2])
```

Q38. Take a list as an input from the user and find the length of the list.
A38.
```python
lst1=input("Enter number of elements seprated by space:").split(" ")
print(len(lst1))
```
Q39. Add the word "Big" in the 3rd index of the given list.
```
lst = ["Welcome", "to", "Data", "course"]
```
A39.
```python
lst = ["Welcome", "to", "Data", "course"]
lst.insert(2, "Big")
print(lst)
```

Q40. What is a tuple? How is it different from list?
A40. Tuple is created by placing all the items (elements) inside parentheses (). A tuple can have any number of items and they may be of different types (integer, float, list, string, etc.) . Tuples are immutable as opposed to lists which are mutable.


Q41. How can you create a tuple in Python?
A41. #empty tuple
    my_tuple =()
    #tuple
    mytuple= (1,2,3)

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.
A42. Unable to add my Name in tuple, because tuple are immutable.
```python
my_tuple=(1, "hello", 3)
my_tuple[1]="Arun"
```

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
A43. yes we can appent two tuples
```python
   tup1=("arun")
   tup2=("Chuahan")
   print(tup1+tup2)
```

Q44. Take a tuple as an input and print the count of elements in it.
A44.
```python
   my_tup=input("write the list of tuple:").slit(" ")
   my_tup =tuple(my_tup)
   print(len(my_tup))
```
Q45. What are sets in Python?
A45. Sets are used to store multiple items in a single variable. Set items are unordered, unchangeable, and do not allow duplicate values.

Q46. How can you create a set?
A46. set = set{} #empty set
     We can create set using curly brackets {}. Keep in mind empty {} will result in dictionary hence there must be some value in the brackets.

Q47. Create a set and add "iNeuron" in your set.
a47. set1 = {"iNeuron"}
    

Q48. Try to add multiple values using add() function.
A48. 
```python
set1.add("classs")
set1.add("start")
set1
```
Q49. How is update() different from add()?
A49. We can add more than one element in a single go using update(), but using add() it's not possible.

Q50. What is clear() in sets?
A50. To remove all the elements from the set, clear() function is used.

Q51. What is frozen set?
A51. While elements of a set can be modified at any time, elements of the frozen set remain the same after creation. 

Q52. How is frozen set different from set?
A52.
- Frozen sets are immutable where as sets are mutable.
- Sets can't be used as keys in dictionary where as frozen sets can be used.

Q53. What is union() in sets? Explain via code.
A53. Python set Union() Method returns a new set which contains all the items from the original set.
```python
set1 = {2, 4, 5, 6}
set2 = {4, 6, 7, 8}
set3 = {7, 8, 9, 10}

print("set1 U set2 : ", set1 | set2)

print("set1 U set2 U set3 :", set1 |set2 | set3)
```
Q54. What is intersection() in sets? Explain via code.
A54. Python set intersection() method returns a new set with an element that is common to all set
```python
set1 = {2, 4, 5, 6}
set2 = {4, 6, 7, 8}
set3 = {4, 6, 8}

print("set1 intersection set2 : ", set1.intersection(set2))

print("set1 intersection set2 intersection set3 :", set1.intersection(set2, set3))
```
Q55. What is dictionary ibn Python?
A55. A dictionary is an unordered and mutable Python container that stores mappings of unique keys to values.

Q56. How is dictionary different from all other data structures.
A56. Dictionary is having key and value pair where as all other data structures have only values in them.

Q57. How can we delare a dictionary in Python?
A57. We can create dictionary using curly brackets {}.

Q58. What will the output of the following?
```
var = {}
print(type(var))
```
A58. dict

Q59. How can we add an element in a dictionary?
A59. 
```python
dict={}
dict[0]="hello"
dict[1]={"class" : ['first class', 'second class', 'third class']}
```

Q60. Create a dictionary and access all the values in that dictionary.
A60.
```python
dict1={}
dict1['name']="Arun"
dict1['experience']=10
dict1['salary']=50000

for i,j in dict1.items():
    print('key in dict1',i, 'and', 'value in dict1', j)

```
Q61. Create a nested dictionary and access all the element in the inner dictionary.
A61.
```python
dict2={'name' : 'Arun', 'expierence': '10 yeras', 'skills' : ['Java', 'Python', 'C++'], 'visted_place': {'country':['sri_lanka', 'bali', 'Nepal'], 'state': ['jakarta', 'colombo']}}

print(dict2['visted_place']['state'][1])
for i , j in dict2.items():
    print(f'key is {i} and value is {j}')
```

Q62. What is the use of get() function?
A62. get() is also to access the elements in dictionary
```python
dict2={'name' : 'Arun', 'expierence': '10 yeras', 'skills' : ['Java', 'Python', 'C++'], 'visted_place': {'country':['sri_lanka', 'bali', 'Nepal'], 'state': ['jakarta', 'colombo']}}
print(dict2.get('name'))
```

Q63. What is the use of items() function?
A63. items() method is used to return the list with all dictionary keys with values.
```python
dict2={'name' : 'Arun', 'expierence': '10 yeras', 'skills' : ['Java', 'Python', 'C++'], 'visted_place': {'country':['sri_lanka', 'bali', 'Nepal'], 'state': ['jakarta', 'colombo']}}

print(dict2.items())
```

Q64. What is the use of pop() function?
A64. pop() is a method. To delete value it uses the index.

Q65. What is the use of popitems() function?
A65. The popitem() method removes the item that was last inserted into the dictionary and and returns it as a tuple.
```python
print(Dict.popitem())
``` 
Q66. What is the use of keys() function?
A66. keys() method returns a view object that displays a list of all the keys Dict = {"Name": "Vishal", "in the dictionary.
```python 
print(Dict.keys())
```

Q67. What is the use of values() function?
A67. values() is an inbuilt method in Python programming language that returns a view object. The view object contains the values of the dictionary, as a list.

Q68. What are loops in Python?
A68. Loops are used the iterate over a block of statement multiple times.

Q69. How many type of loop are there in Python?
A69. There is for and while loop in Python

Q70. What is the difference between for and while loops?
A70. When we know the exact number of iterations, we can use for loop. When we want the to run till a certain condition is true we can use while loop.

Q71. What is the use of continue statement?
A71. Continue Statement skips the execution of the program block from after the continue statement and forces the control to start the next iteration.

Q72. What is the use of break statement?
A72. 'Break' in Python is a loop control statement. It is used to control the sequence of the loop. 

Q73. What is the use of pass statement?
A73. The pass statement in Python is used when a statement is required syntactically but you do not want any command or code to execute.

Q74. What is the use of range() function?
A74. range() function returns a sequence of numbers, in a given range. The most common use of it is to iterate sequence on a sequence of numbers.

Q75. How can you loop over a dictionary?
A75.
```python
dict2={'name' : 'Arun', 'expierence': '10 yeras', 'skills' : ['Java', 'Python', 'C++'], 'visted_place': {'country':['sri_lanka', 'bali', 'Nepal'], 'state': ['jakarta', 'colombo']}}

for i in dict2:
    print(i)

``` 


### Coding problems

Q76. Write a Python program to find the factorial of a given number.
A76.
```python

def factorial (n):
    if n<0:
        return 0
    elif n==0 and n ==1:
        return 1
    else:
        fact = 1
        while(n>1):
            fact = fact * n
            n -= 1
        return fact    
ab = 5
print(factorial(ab))
```

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100
A77.
```python
def simpleIntersest(p,t,r=2.5):
    SI= (p*t*r)/100
    return SI
     
principal = 1000
time= 2
rate= 10

print(simpleIntersest(100, 1))
```

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.
A78.
```python
def compoundInterset(p, t, r):
    amount= p*(1+ r/100)**t
    CI= amount - p
    print(f"compound interest {CI}")
    return CI

compoundInterset(1000, 2, 10)
```

Q79. Write a Python program to check if a number is prime or not.
A79.
```python
from math import sqrt

def is_prime(n):
  prime_flag = 0

  if(n > 1):
    for i in range(2, int(sqrt(n)) + 1):
      if (n % i == 0):
        prime_flag = 1
        break
    if (prime_flag == 0):
      print(f"{n} is a prime number.")
    else:
      print(f"{n} is not a prime number.")
  else:
    print(f"{n} is not a prime number.")

is_prime(5)      
```

Q80. Write a Python program to check Armstrong Number.
```python
def check_armstrong(n):
  s = n
  b = len(str(n))
  sum1 = 0
  while n != 0:
      r = n % 10
      sum1 = sum1+(r**b)
      n = n//10
  if s == sum1:
      print(f"The given number {s} is armstrong number")
  else:
      print(f"The given number {s} is not armstrong number")

check_armstrong(153)
```
Q81. Write a Python program to find the n-th Fibonacci Number.
A81. 
```python
def Fibonacci(n):
	if n<= 0:
		print("Incorrect input")
	elif n == 1:
		return 0
	elif n == 2:
		return 1
	else:
		return Fibonacci(n-1)+Fibonacci(n-2)

print(Fibonacci(5)) 
```

Q82. Write a Python program to interchange the first and last element in a list.
A82.
```python
list1= [ 1,2,3,4,5,6]
def changeFirstToLast(n):
    length1=len(n)
    temp = n[0]
    n[0]=n[length1 -1]
    n[length1-1]= temp
    return n

print(changeFirstToLast(list1))    
```
Q83. Write a Python program to swap two elements in a list.
```python
def swapPositions(list, pos1, pos2):
	
	list[pos1], list[pos2] = list[pos2], list[pos1]
	return list

List = [15, 12, 35, 17, 9, 56, 29]
pos1, pos2 = 1, 3

print(f"Original list: {List}")
print(f"Swapped list: {swapPositions(List, pos1, pos2)}")
```

Q84. Write a Python program to find N largest element from a list.
A84. 
```python
def max_listof_list(list, N):
    final_list=[]

    for i in range(0,N):
        max=0

        for j in range(len(list)):
            if list[j]>max:
                max=list[j];
        list.remove(max)
        final_list.append(max)
   return final_list

list1=[100, 20, 40, 80, 50, 40, 69]
N= 3
print(max_listof_list(list1, N))
```
Q85. Write a Python program to find cumulative sum of a list.
A85.
```python
def cum_sum_list(list1):
    final_cum_list=[]
    for i in  range(1, len(list1)+1):
        sum1= sum(list1[0:i])
        final_cum_list.append(sum1)

    return final_cum_list

list_num=[4, 10, 18, 9, 14, 22, 11, 36]	
print(cum_sum_list(list_num))
```
        

Q86. Write a Python program to check if a string is palindrome or not.
A86.
```python
def palindorme_string(str1):
    if str1==str1[::-1]:
        print("string is palindrome")
    else:
        print("string is not palindrome")
    return

test_str="ABCDCBA"
palindorme_string(test_str)

```


Q87. Write a Python program to remove i'th element from a string.
```python
def remove_nelemet(str1, n):
    if len(str1)>n and len(str1)!=0:
        str2= list(str1)
        del str2[n]
        print("".join(str2))
    else:
       print("write a vaild ith position")

    return

string1="loveyouforever"
remove_nelemet(string1,13)
```

Q88. Write a Python program to check if a substring is present in a given string.
A88.
```python
def check_sub_string(str1, st2):
    if (str1.count(st2) > 0):
        print(f' "{str1}" is a substring of "{st2}"')
    else:
        print(f' "{str1}" is not a substring of "{st2}"')

    return
s1 = "welcome to the data engineer"
s2 = "data"
check_sub_string(s1,s2)
```

Q89. Write a Python program to find words which are greater than given length k.
Ans. 
```python
def check_string_gtr_k(k,str):
	string=[]

	text = str.split(" ")

	for x in text:
		if len(x) > k:
			string.append(x)



	return string

k= 3
str1="Do you know Data engineer"

print(check_string_gtr_k(k, str1))
```


Q90. Write a Python program to extract unquire dictionary values.
Ans.
```python
test_dict = {'iNeuron': [5, 6, 7, 8],
			'is': [10, 11, 7, 5],
			'best': [6, 12, 10, 8],
			'for': [1, 2, 5],
      'big data': [2, 7, 12, 9]
      }

print("The original dictionary is : " + str(test_dict))

res = list(sorted({ele for val in test_dict.values() for ele in val}))

print("The unique values list is : " + str(res))
```

Q91. Write a Python program to merge two dictionary.
```python
dict1={'top':34,
'innings':98,
'name': 'rohit',
'fifty':49
}

dict2={'name':'Arun',
 'age':31, 
 'total':'value',
 'color':'White'
}

dict1.update(dict2)
print(dict1)
```

Q92. Write a Python program to convert a list of tuples into dictionary.
```
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
```
Ans.
```python
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]

output= dict(Input)
print(output)
```
Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
```
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
```
Ans.
```python
Input = [9, 5, 6]
output = [(val, val **3) for val in Input]
```

Q94. Write a Python program to get all combinations of 2 tuples.
```
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
```
Ans.
```python
test_tuple1 = (7, 2)
test_tuple2 = (7, 8)

res = [(a, b) for a in test_tuple1 for b in test_tuple2]
res = res + [(a, b) for a in test_tuple2 for b in test_tuple1]
print(res)
```

Q95. Write a Python program to sort a list of tuples by second item.
```
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
```
Ans.
```python
Input = [('for', 24), ('Geeks', 8), ('Geeks', 30)] 

```
Ans.
```Python
def sort_tuple(tup):
    lst = len(tup)
    for i in range(0, lst):
        for j in range(0, lst-i-1):
            if (tup[j][1] > tup[j+1][1]):
                temp = tup[j]
                tup[j]=tup[j+1]
                tup[j+1]= temp
    return tup   

Input = [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
print(sort_tuple(Input))         
```

Q96. Write a python program to print below pattern.
```
* 
* * 
* * * 
* * * * 
* * * * * 
```
Ans.
```python
def py_pattern(n):
    for i in range(0, n):
        for j in range( 0, i+1):
            print("* " , )

n = 5
py_pattern(n)            
```

Q97. Write a python program to print below pattern.
```
    *
   **
  ***
 ****
*****
```
Ans. 
```python
def inverse_pattern():
    n=5;i=0
    while(i<=n):
        print(" "*(n-i) + "*" * i)
        i +=1
inverse_pattern()        
```

Q98. Write a python program to print below pattern.
```
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
```
Ans.
```python
def triangle_pattern():
    K = n -1 
    for i in range(0, n):

        for j in range(0, k):
            print(end=" ")

        k = k-1

        for j in range(0 , i + 1):
             print("* " , end ="")

        print("\r")
n = 5
triangle_pattern(n)        

```

Q99. Write a python program to print below pattern.
```
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
```
Ans.
```python
def number(n):
    for i in range(1, n+1):
        for j in range(1, i+1):
            print(j, end=" ")
        print("\r")    


    return
     
num = 5
number(num)
```


Q100. Write a python program to print below pattern.
```
A 
B B 
C C C 
D D D D 
E E E E E 
```
Ans.
```python
def alphapat(n):

	num = 65

	for i in range(0, n):
	
		for j in range(0, i+1):

			ch = chr(num)
		
			print(ch, end=" ")
	
		num = num + 1
	
		print("\r")

n = 5
alphapat(n)
```
