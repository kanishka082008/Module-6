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
```
class Rectangle:
    
    def __init__(self, length, breadth):
        self.__length = length      
        self.__breadth = breadth    
        self.display_dimensions()  

    
    def display_dimensions(self):
        print(f"Length: {self.__length}")
        print(f"Breadth: {self.__breadth}")


rect = Rectangle(10, 5)
```

## Output
<img width="1108" height="293" alt="image" src="https://github.com/user-attachments/assets/2d34dd38-fd1c-4aea-b953-38f7ac6eda78" />

## Result
the code is executed
