# Exp.No:23  
## Multiple Inheritance

### AIM  
To Write a Python program to Get the name, roll no and 4 marks of a student and find & display the total marks and Average using Multilevel inheritance.

### ALGORITHM
1.Define the Grandparent Class (Base Class):
This class will contain the basic details of the student, such as name and roll_no.
Create a constructor (__init__) to initialize these attributes.
Create a method to display the student’s basic details (name and roll number).
2.Define the Parent Class:
This class will inherit from the grandparent class.
It will call the constructor of the grandparent class using super() to initialize the inherited attributes.
It will add functionality for handling marks (four subjects).
Add a method to display the marks.
3.Define the Child Class:
This class will inherit from the parent class.
It will call the constructor of the parent class using super() to initialize all inherited attributes.
It will calculate the total marks and the average marks.
4.Create a method to display the total marks and average.
Create an Object of the Child Class:
Create an instance of the child class, input the details (name, roll number, and marks).
The child class will display the total and average marks by calling the relevant method.

### PROGRAM
class Name:
    def __init__(self, name):
        self.name = name

class Roll(Name):
    def __init__(self, name, roll):
        super().__init__(name)
        self.roll = roll

class Marks(Roll):
    def __init__(self, name, roll, m, p, c, t):
        super().__init__(name, roll)
        self.m = m
        self.p = p
        self.c = c
        self.t = t

    def print_details(self):
        total = self.m + self.p + self.c + self.t
        average = total / 4
        print(f"Name:  {self.name} Rollno:  {self.roll} Total Marks out of 400:  {total}")
        print(f"Average : {average:.2f}")

name = input()
roll = int(input())
m = int(input())
p = int(input())
c = int(input())
t = int(input())

obj = Marks(name, roll, m, p, c, t)
obj.print_details()

### OUTPUT
![image](https://github.com/user-attachments/assets/643f5b03-d0e1-4d61-87a2-b7d42238e5f2)

### RESULT
Thus,a Python program to Get the name, roll no and 4 marks of a student and find & display the total marks and Average using Multilevel inheritance was implemented and successfully executed.






