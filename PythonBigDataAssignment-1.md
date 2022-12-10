## Assignment Part-1

Q1. Why do we call Python as a general purpose and high-level programming language?
A1. Python is computer programming language often used to build website and software and many other applications. Due to its dymanic sementics and object oreiented called as high level programming language.

Q2. Why is Python called a dynamically typed language?
A2. In python, the declration of variable type is not important whereas in other programming language like c, c++, java etc there is strict decleration of variable before assigning value.

Q3. List some pros and cons of Python programming language?
A3. pros:-   It is easy to learn and read
             python has vast collection of libraries
             python is free, open-source, and has a vibrant community
    cons:-   slow soeed
             runtime error        
             Python consumes a lot of memory space

Q4. In what all domains can we use Python?
A4. Python is used for artificial intelligence, machine learning, deep learnimg, data science, scientific computing, Scripting , game deveploment and web development.

Q5. What are variable and how can we declare them?
A5. Variable are the unit of strorage in programming language and these variable consist data type, variable name, and value assigned to the variable. 
    VariableName = value.

Q6. How can we take an input from the user in Python?
A6. In Python input can be read using input() built-in function.

Q7. What is the default datatype of the value that has been taken as an input using input() function?
A7. Datatype of the input  function can be taken as string, int, float . 

Q8. What is type casting?
A8. Type casting can be define as chanhing the variable datatype into another datatype. example
    Number_of_player = 11  #here the data type is int datatype
    number_of_player = str(Number_of_player) #here after typecasting datatype int varaiable change into string datatype

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
A9. Yes we can take multiple input from input function.
    x, y = input("enter two color of choice:").split()
    print("first color{} and second color{}".format(x,y))

Q10. What are keywords?
A10. keyword are predefined and reserved words in python that have speacial meaning. 

Q11. Can we use keywords as a variable? Support your answer with reason.
A12. The keyword cannot be used as an identifier, function, and variable name. Beause they are used to define the synatx and structure of python language. except true, false and none.

Q12. What is indentation? What's the use of indentaion in Python?
A12. Indentation are the spaces at the begining of a code line. The indentation in python indicate a block of code.

Q13. How can we throw some output in Python?
A13. In python we can use Print() function to throw output in python.

Q14. What are operators in Python?
A15. In python operators are symbols that designate that some computation should be performed. like +,-,* etc.

Q15. What is difference between / and // operators?
A16. The division oprator(/) gives an output in floating point whereas the (//) produce result in rounded to the next smallest whole number.

Q16. Write a code that gives following as an output.
A17. data = "iNeuron"
     print(data * 4)
```
iNeuroniNeuroniNeuroniNeuron
```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
A17. number = int(input("write the number to check for even or odd: "))
     if number%2==0:
         print(number,"is even number")
    else:
         print(number,"is odd number")

Q18. What are boolean operator?
A18. Boolean Operators are simple words used as conjunctions to combine or exclude keywords in a search (AND, OR, NOT or AND NOT)

Q19. What will the output of the following?
```
1 or 0 = True

0 and 0 = True

True and False and True = False

1 or 0 or 0  = True
```

Q20. What are conditional statements in Python?
A20.  conditional statement is used to handle conditions in your program

Q21. What is use of 'if', 'elif' and 'else' keywords?
A21. if...elif...else is used in Python for decision making. It is use to specify a block of code to be excuted.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
A22.
age= int(input("enter you age :"))
if age>=18:
    print("I can vote")
else:
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
sum_of_even_number= 0
numbers = [12, 75, 150, 180, 145, 525, 50]
for num in numbers:
    if num%2==0:
        sum_of_even_number=sum_of_even_number+num
print(sum_of_even_number)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
A24.
x, y, z = input("write three numbers:").split()
list=[]
list.append(int(x))
list.append(int(y))
list.append(int(z))
print(list)
print(max(list))

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
A25.
numbers = [12, 75, 150, 180, 145, 525, 50, ]
list=[]
for num in numbers:
    if num>500:
        break
    if num%5==0 and num >150:
        list.append(num)
print(list)    