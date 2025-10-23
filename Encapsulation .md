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
class Rectangle:
    def __init__(self, length, breadth):
        self.__length = length     # Private variable
        self.__breadth = breadth   # Private variable

    def set_length(self, length):
        self.__length = length

    def set_breadth(self, breadth):
        self.__breadth = breadth

    def get_length(self):
        return self.__length

    def get_breadth(self):
        return self.__breadth
    def calculate_area(self):
        return self.__length * self.__breadth


rect = Rectangle(10, 5)

print("Length:", rect.get_length())
print("Breadth:", rect.get_breadth())

rect.set_length(12)
rect.set_breadth(6)

print("Updated Length:", rect.get_length())
print("Updated Breadth:", rect.get_breadth())

print("Area of Rectangle:", rect.calculate_area())
```
## Output
<img width="255" height="116" alt="image" src="https://github.com/user-attachments/assets/ab36d897-d8b1-460f-96f8-16420aacf562" />

## Result
Thus a python program to write a python program to overload a comparison operator has been written and executed successfully.
