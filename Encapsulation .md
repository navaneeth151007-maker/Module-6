# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```c
class A:
    def __init__(self,a):
        self.a=a
    def __gt__(self,other):
        return self.a>other.a
ob1=A(2)
ob2=A(3)
if ob2>ob1:
    print("ob2 is greater than ob1")
else:
    print("ob1 is greater than ob2")
```
## Output
<img width="242" height="28" alt="image" src="https://github.com/user-attachments/assets/54c99f4e-1e63-4b47-86bc-ece9bd241a05" />

## Result
Thus a python program to write a python program to overload a comparison operator has been written and executed successfully.
