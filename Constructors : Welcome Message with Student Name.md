# # Constructors in Python: Welcome Message with Student Name

## 🎯 Aim
To write a Python program that creates a **Student** class with a **default constructor** and a method to display a welcome message along with the student’s name provided by the user.

## 🧠 Algorithm
1. **Get user input**: Accept the student's name from the user.
2. **Define the class**: Create a class `Student` with a default constructor (`__init__`).
3. **Default Constructor**: In the constructor, assign the user input (student name) to an instance variable `self.a`.
4. **Display Message**: Define a method `show` that prints "This is non-parameterized constructor" and a welcome message with the student’s name.
5. **Execute the Program**: Instantiate the `Student` class and call the `show` method.

## 🧾 Program

~~~~
class student:
    def _init_(self):
        print("This is non parametrized constructor")
    def display(self,name):
        self.name=name
        print("Hello",self.name)
s=student()
s.display(input())
~~~~

## Output
<img width="1120" height="251" alt="image" src="https://github.com/user-attachments/assets/64b53e63-59c9-42f9-b7ad-dbb3d3a9f1d3" />

## Result
Thus th python program is executed successfully.
