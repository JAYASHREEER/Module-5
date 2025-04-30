# Exp.No:21  
## Constructors - Parameterized Constructor

### AIM  
The aim of this task is to create a Python class that represents a "Person." This class should have a parameterized constructor that accepts the name and userid of the person, and prints the userid when an instance of the class is created.

### ALGORITHM
1.Define a class named Person.
2.Create the __init__ method (constructor):
This method should accept two parameters: name and userid.
The __init__ method should initialize these parameters as instance variables.
3.Print the userid inside the constructor to display it when a new object of the class is created.
4.Test the class by creating an instance of Person and passing the name and userid as arguments.

### PROGRAM
class Person:
    def __init__(self,name,userid):
        self.name=name
        self.userid=userid
name=input()
userid=input()
det=Person(name,userid)
print(getattr(det,"userid"))

### OUTPUT
![image](https://github.com/user-attachments/assets/3477cb1a-4123-4951-8dd7-2177cf6b119c)

### RESULT
Thus,the Python class that represents a "Person." This class should have a parameterized constructor that accepts the name and userid of the person, and prints the userid when an instance of the class is created was implemented and successfully executed.
