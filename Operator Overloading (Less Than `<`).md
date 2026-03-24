# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
~~~
# Operator overloading example

class A:
    def __init__(self, a):
        self.a = a

    def __lt__(self, o):
        if self.a < o.a:
            return "ob1 is less than ob2"
        else:
            return "ob2 is less than ob1"

# Create objects
ob1 = A(10)
ob2 = A(20)

# Compare objects
print(ob1 < ob2)
~~~
## Output
<img width="415" height="195" alt="Screenshot 2026-03-24 145254" src="https://github.com/user-attachments/assets/32b18114-4568-4343-b0cb-7fac1cb99f91" />

## Result
Thus, the Python program demonstrating operator overloading using the less than (<) operator was successfully executed and verified.
