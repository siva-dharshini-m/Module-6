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
          print("Length:", self.__length)
          print("Breadth:", self.__breadth)
  
  rect = Rectangle(10, 5)  class Rectangle:
      def __init__(self, length, breadth):
          self.__length = length
          self.__breadth = breadth
          print("Length:", self.__length)
          print("Breadth:", self.__breadth)
  
  rect = Rectangle(10, 5)
```
## Output
![e5e71a6b-fd78-43b8-a25a-37feb4f30473](https://github.com/user-attachments/assets/62dfd17d-0d3e-4eb9-917a-29cd99a65b4c)

## Result
Thus, the program is successfully executed
