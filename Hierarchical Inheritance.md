# Exp.No:25  
## Hierarchical Inheritance

### AIM  
To write a Python program to get the employee and doctor details and display them using hierarchical inheritance. Create a parent (base) class named `Details` and two child (derived) classes named `Employee` and `Doctor`.

### ALGORITHM
1.Define the Parent Class Details:
This class will contain common attributes such as name, age, and address, which will be shared between both employees and doctors.
The class should have a constructor (__init__) to initialize these common attributes.
Create a method to display the details of the person.
2.Define the Child Class Employee:
This class will inherit from Details.
It will add employee-specific attributes such as employee_id and department.
The class will contain a method to display the employee details.
3.Define the Child Class Doctor:
This class will also inherit from Details.
It will add doctor-specific attributes such as doctor_id and specialization.
The class will contain a method to display the doctor details.
4.Create Objects:
Create instances of Employee and Doctor and call their methods to display their respective details.

### PROGRAM
class Details:
    def __init__(self):
        self.eid=eid
        self.ename=ename
        self.egen=egen
        self.ecomp=ecomp
        self.edept=edept
        self.did=did
        self.dname=dname
        self.dgen=dgen
        self.dhos=dhos
        self.ddept=ddept
class Employee(Details):
    def showe(self):
        print("Id: ",self.eid)
        print("Name: ",self.ename)
        print("Gender: ",self.egen)
        print("Company: ",self.ecomp)
        print("Department: ",self.edept)
class Doctor(Details):
    def showd(self):
        print("Id: ",self.did)
        print("Name: ",self.dname)
        print("Gender: ",self.dgen)
        print("Hospital: ",self.dhos)
        print("Department: ",self.ddept)
eid=int(input())
ename=input()
egen=input()
ecomp=input()
edept=input()
did=int(input())
dname=input()
dgen=input()
dhos=input()
ddept=input()
print("Employee Object")
e=Employee()
e.showe()
print("\nDoctor Object")
d=Doctor()
d.showd()
    
### OUTPUT  
![image](https://github.com/user-attachments/assets/d58788a7-bc71-4e2b-b6ae-284c605f1553)

### RESULT
Thus, Python program to get the employee and doctor details and display them using hierarchical inheritance. Create a parent (base) class named `Details` and two child (derived) classes named `Employee` and `Doctor` was implemented and successfully executed.

