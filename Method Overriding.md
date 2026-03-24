# 🐟 Method Overriding-Fish and Shark Class Inheritance in Python

## 🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method.

## 📋 ALGORITHM:

1. Define the `Fish` class with a method named `type()` that prints `"fish"`.
2. Define the `Shark` class as a subclass of `Fish`, and override the `type()` method to print `"shark"`.
3. Create an instance of the `Fish` class named `obj_goldfish`.
4. Create an instance of the `Shark` class named `obj_hammerhead`.
5. Use a `for` loop to iterate over both objects.
6. Within the loop, call the `type()` method using the loop variable.
7. Output will demonstrate method overriding: printing `"fish"` and `"shark"` accordingly.

## 💻 PROGRAM:
~~~
# Method overriding example

class Fish:
    def type(self):
        print("fish")

class Shark(Fish):
    def type(self):
        print("shark")

# Create objects
obj_goldfish = Fish()
obj_hammerhead = Shark()

# Loop through objects
for obj in (obj_goldfish, obj_hammerhead):
    obj.type()
~~~
## OUTPUT
<img width="451" height="236" alt="Screenshot 2026-03-24 145059" src="https://github.com/user-attachments/assets/ff08c123-31db-4723-b8a9-7ea406ca4677" />

## RESULT
Thus, the Python program demonstrating method overriding using inheritance was successfully executed and verified.
