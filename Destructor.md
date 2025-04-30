# Exp.No:22  
## Destructor

### AIM  
The aim of this task is to create a Python class Student that uses a destructor. The class should initialize an object with a message when created, print a custom greeting, and then print a message when the object is destroyed, demonstrating the use of a destructor.

### ALGORITHM
1.Define a class named Student.
2.Create the __init__ method (constructor):
This method should print a message indicating the object has been initialized and display a greeting message containing the student's name.
3.Create the __del__ method (destructor):
The destructor should print a message indicating that the object is being destroyed.
4.Test the class:
Create an instance of Student and observe the constructor and destructor messages.
Ensure the destructor is called when the object is deleted or goes out of scope.

### PROGRAM
class Student:
    def __init__(self, name):
        print("Inside Constructor")
        print("Object initialized")
        self.name = name

    def greet(self):
        print(f"Hello, my name is {self.name}")

    def __del__(self):
        print("Inside destructor")
        print("Object destroyed")

student = Student("Emma")
student.greet()
del student

### OUTPUT
![image](https://github.com/user-attachments/assets/d410b6ec-8031-4a86-92d4-49d0917f50aa)

### RESULT
Thus,Python class Student that uses a destructor and The class should initialize an object with a message when created, print a custom greeting, and then print a message when the object is destroyed, demonstrating the use of a destructor was implemented and successfully executed.
