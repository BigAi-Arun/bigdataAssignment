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

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
A24.
x, y, z = input("write three numbers:").split()
list=[]
list.append(int(x))
list.append(int(y))
list.append(int(z))
print(list)
print(max(list))