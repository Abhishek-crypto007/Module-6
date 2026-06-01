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
```python3
class Rectangle:
  __length = 0 #private variable
  __breadth = 0#private variable
  def __init__ (self,__length,__breadth):
    #constructor
    self.__length = 5
    self.__breadth = 3
    print(self.__length)
    print(self.__breadth)
 
rect = Rectangle(5,3)



```

## Output
<img width="1364" height="918" alt="image" src="https://github.com/user-attachments/assets/4f5c6da6-5ad0-4215-aca6-76c79454c927" />

## Result
Thus the python program to implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth` has been done successfully.
