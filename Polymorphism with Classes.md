# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
```c
class Beans:
    def type(self):
        print("I am a Vegetable.")

    def color(self):
        print("My color is Green.")

class Mango:
    def type(self):
        print("I am a Fruit.")

    def color(self):
        print("My color is Yellow.")

def describe(item):
    item.type()
    item.color()

b = Beans()
m = Mango()

print("Details of Beans:")
describe(b)

print("\nDetails of Mango:")
describe(m)

```
## Output
<img width="212" height="185" alt="image" src="https://github.com/user-attachments/assets/fb98a6d0-408c-4f69-8f95-5003853e047f" />

## Result
Thus, the Python program was successfully executed to demonstrate Polymorphism with Classes using a generic function that works with both Beans and Mango objects to display their type and color.
