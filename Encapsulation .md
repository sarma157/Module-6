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
    def __init__(self):
        self.__length = 10
        self.__breadth = 5
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)

r = Rectangle()
```
## Output
<img width="572" height="147" alt="image" src="https://github.com/user-attachments/assets/30127deb-f4ec-4b88-b8dd-99aec4c5a6f6" />

## Result
The private member variables __length and __breadth were successfully implemented using encapsulation and displayed within the class.
