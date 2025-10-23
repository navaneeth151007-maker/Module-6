# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.

---

## 🧠 ALGORITHM

1. **Import ABC module**:
   - Use `from abc import ABC, abstractmethod` to define abstract classes and methods.

2. **Create Abstract Class `Shape`**:
   - Define an abstract method `calculate_area()` with `@abstractmethod`.

3. **Create Subclass `Rectangle`**:
   - Set default values for `length` and `breadth`.
   - Override `calculate_area()` to compute the rectangle area.

4. **Create Subclass `Circle`**:
   - Set default value for `radius`.
   - Override `calculate_area()` to compute the circle area.

5. **Create Objects & Call Methods**:
   - Instantiate `Rectangle` and `Circle`.
   - Call their `calculate_area()` methods.

---

## 💻 Program
```c
class Cat:
    def mood(self):
        print("Grumpy")
    def sound(self):
        print("Meow")
 
class Dog:
    def mood(self):
        print("Happy")
    def sound(self):
        print("Woof")
 
hello_kitty = Cat()
hello_puppy = Dog()
 
for pet in (hello_kitty, hello_puppy):
    pet.mood()
    pet.sound()
```
## Output
<img width="190" height="98" alt="image" src="https://github.com/user-attachments/assets/85b27fe0-7b61-4ba1-aa8d-f62b18faf223" />

## Result
Thus a python program to create two classes with functions mood() and sound() has been written and executed successfully.
