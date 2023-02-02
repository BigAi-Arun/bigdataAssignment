## Python OOP Assignment
Q1. What is the purpose of Python's OOP?
Ans1. In Python, object-oriented Programming (OOPs) is a programming paradigm that uses objects and classes in programming. It aims to implement real-world entities like inheritance, polymorphisms, encapsulation, etc. in the programming.

Q2. Where does an inheritance search look for an attribute?
A2. An inheritance search looks for an attribute first in the instance object, then in the class the instance was created from, then in all higher superclasses, progressing from left to right.

Q3. How do you distinguish between a class object and an instance object?
A3. The class = the blue print. The Object is an actual thing that is built based on the 'blue print'. An instance is a virtual copy (but not a real copy) of the object.

Q4. What makes the first argument in a class’s method function special?
A4. meth(args) becomes Class.
This is the reason the first parameter of a function in class must be the object itself. Writing this parameter as self is merely a convention. It is not a keyword and has no special meaning in Python.

Q5. What is the purpose of the init method?
A5. The __init__ method is the Python equivalent of the C++ constructor in an object-oriented approach. The __init__ function is called every time an object is created from a class. The __init__ method lets the class initialize the object's attributes and serves no other purpose.

Q6. What is the process for creating a class instance?
A6.To create instances of a class, you call the class using class name and pass in whatever arguments its __init__ method accepts.

Q7. What is the process for creating a class?
A7.create class.
 Enter the class name. To enter a short description, grade level, or class time, tap Section and enter the details. To enter the location for the class, tap Room and enter the details.

Q8. How would you define the superclasses of a class?
A8. The class from which a class inherits is called the parent or superclass. A class which inherits from a superclass is called a subclass, also called heir class or child class. Superclasses are sometimes called ancestors as well.

Q9. What is the relationship between classes and modules?
A9. Modules are collections of methods and constants. They cannot generate instances. Classes may generate instances (objects), and have per-instance state (instance variables).

Q10. How do you make instances and classes?
A10. To create instances of a class, you call the class using class name and pass in whatever arguments its __init__ method accepts.

Q11. Where and how should be class attributes created?
A11. A class attribute is shared by all instances of the class. To define a class attribute, you place it outside of the __init__() method.

Q12. Where and how are instance attributes created?
A12. A class attribute is shared by all instances of the class. To define a class attribute, you place it outside of the __init__() method. Use class attributes for storing class contants, track data across all instances, and setting default values for all instances of the class.

Q13. What does the term "self" in a Python class mean?
A13. SELF represents the instance of class. This handy keyword allows you to access variables, attributes, and methods of a defined class in Python. The self parameter doesn't have to be named “self,” as you can call it by any other name.

Q14. How does a Python class handle operator overloading?
A14. To perform operator overloading, Python provides some special function or magic function that is automatically invoked when it is associated with that particular operator.

Q15. When do you consider allowing operator overloading of your classes?
A15. Operator overloading is mostly useful when you're making a new class that falls into an existing "Abstract Base Class".

Q16. What is the most popular form of operator overloading?
A16. A very popular and convenient example is the Addition (+) operator. Just think how the '+' operator operates on two numbers and the same operator operates on two strings. It performs “Addition” on numbers whereas it performs “Concatenation” on strings.

Q17. What are the two most important concepts to grasp in order to comprehend Python OOP code?
A17. Both inheritance and polymorphism are fundamental concepts of object oriented programming. These concepts help us to create code that can be extended and easily maintainable.

Q18. Describe three applications for exception processing.
A18. Exception handling is useful for dealing with exceptions that cannot be handled locally. Instead of showing an error status in the program, the exception handler transfers control to where the error can be handled. A function can throw exceptions or can choose to handle exceptions.

Q19. What happens if you don't do something extra to treat an exception?
A19. When an exception occurred, if you don't handle it, the program terminates abruptly and the code past the line that caused the exception will not get executed.

Q20. What are your options for recovering from an exception in your script?
A20. You can also provide a generic except clause, which handles any exception. After the except clause(s), you can include an else-clause. The code in the else-block executes if the code in the try: block does not raise an exception. The else-block is a good place for code that does not need the try: block's protection.

Q21. Describe two methods for triggering exceptions in your script.
A21. Handling Exceptions
First, the try clause (the statement(s) between the try and except keywords) is executed.
If no exception occurs, the except clause is skipped and execution of the try statement is finished.
If an exception occurs during execution of the try clause, the rest of the clause is skipped.

Q22. Identify two methods for specifying actions to be executed at termination time, regardless of  
whether or not an exception exists.
A22. 


Q23. What is the purpose of the try statement?
A23.The try block lets you test a block of code for errors. 

Q24. What are the two most popular try statement variations?
A24. There are two other optional segments to a try block: else and finally . Both of these optional blocks will come after the try and the except . Also, there's nothing stopping you from using both else and finally in a single statement — but keep them in that order if you do.

Q25. What is the purpose of the raise statement?
A25. Python raise Keyword is used to raise exceptions or errors. The raise keyword raises an error and stops the control flow of the program. It is used to bring up the current exception in an exception handler so that it can be handled further up the call stack.

Q26. What does the assert statement do, and what other statement is it like?
A26. The assert keyword is used when debugging code. The assert keyword lets you test if a condition in your code returns True, if not, the program will raise an AssertionError.

Q27. What is the purpose of the with/as argument, and what other statement is it like?
A27. The with statement replaces a try-catch block with a concise shorthand. More importantly, it ensures closing resources right after processing them. A common example of using the with statement is reading or writing to a file.

Q28. What are *args, **kwargs?
A28. *args specifies the number of non-keyworded arguments that can be passed and the operations that can be performed on the function in Python whereas **kwargs is a variable number of keyworded arguments that can be passed to a function that can perform dictionary operations.

Q29. How can I pass optional or keyword parameters from one function to another?
A29. A type of argument with a default value is a Python optional parameter. A function definition's assignment operator or the Python **kwargs statement can be used to assign an optional argument.

Q30. What are Lambda Functions?
A30. Lambda runs your code on a high-availability compute infrastructure and performs all of the administration of the compute resources, including server and operating system maintenance, capacity provisioning and automatic scaling, and logging.

Q31. Explain Inheritance in Python with an example?
A31. Inheritance is a mechanism in which one class acquires the property of another class. For example, a child inherits the traits of his/her parents. With inheritance, we can reuse the fields and methods of the existing class.

Q32. Suppose class C inherits from classes A and B as class C(A,B).Classes A and B both have their own versions of method func(). If we call func() from an object of 
class C, which version gets invoked?
A32.The version of the func() method that gets invoked depends on the method resolution order (MRO) of class C. The MRO determines the order in which the parent classes are searched for a method. In the case of class C inheriting from A and B as class C(A,B), the MRO of C would be [C, A, B].

This means that when func() is called on an object of class C, the method will be searched for first in the class C, then in class A, and finally in class B. The first occurrence of the method found in the MRO will be the one that is invoked.

Q33. Which methods/functions do we use to determine the type of instance and inheritance?
A33. Using isinstance() function, we can test whether an object/variable is an instance of the specified type or class such as int or list. In the case of inheritance, we can checks if the specified class is the parent class of an object.

Q34.Explain the use of the 'nonlocal' keyword in Python.
A34. The nonlocal keyword is used to work with variables inside nested functions, where the variable should not belong to the inner function.

Q35. What is the global keyword?
A35. Global keyword is used to modify the global variable outside its current scope and meaning.