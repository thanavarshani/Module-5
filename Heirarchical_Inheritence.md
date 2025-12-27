# Hierarchical Inheritance in Python

This Python project demonstrates **Hierarchical Inheritance** using a base class `Details` and two derived classes `Employee` and `Patient`. The program collects and displays details for both employees and patients.

## 🎯 Aim

To write a Python program that uses **Hierarchical Inheritance** to input and display **Employee** and **Patient** details.

## 📘 Description

- **Base Class:** `Details`
  - Stores common attributes: `name`, `age`
  - Provides methods: `getName()`, `getAge()`

- **Derived Class 1:** `Employee`
  - Inherits from `Details`
  - Adds: `employee_id`, `department`
  - Method: `getEmployeeDetails()`

- **Derived Class 2:** `Patient`
  - Inherits from `Details`
  - Adds: `patient_id`, `disease`
  - Method: `getPatientDetails()`

## 🧠 Algorithm

1. Create base class `Details` with common attributes.
2. Create `Employee` class extending `Details`, adding employee-specific data.
3. Create `Patient` class extending `Details`, adding patient-specific data.
4. Get user input for employee and patient data.
5. Display collected information using class methods.

## Program
~~~~
class mec:
    def _init_(self,a,b,c,d,e,f,g,h,i,j):
        self.a=a
        self.b=b
        self.c=c
        self.d=d
        self.e=e
        self.f=f
        self.g=g
        self.h=h
        self.i=i
        self.j=j
        print("Employee Object")
        print(f"Id:  {a}")
        print(f"Name:  {b}")
        print(f"Gender:  {c}")
        print(f"Company:  {d}")
        print(f"Department:  {e}")
        print()
        print("Patient Object")
        print(f"Id:  {f}")
        print(f"Name:  {g}")
        print(f"Gender:  {h}")
        print(f"Hospital:  {i}")
        print(f"Department:  {j}")
a=input()
b=input()
c=input()
d=input()
e=input()
f=input()
g=input()
h=input()
i=input()
j=input()
m=mec(a,b,c,d,e,f,g,h,i,j)
~~~~
## Sample Output
<img width="592" height="456" alt="image" src="https://github.com/user-attachments/assets/720aa9a3-cd13-4eef-ada8-7256ba84efd6" />

## Result
Thus the python program has been successfully executed.
