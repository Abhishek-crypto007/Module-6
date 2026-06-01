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

## 💻 Program:
```python3
import math 
from abc import ABC
class type_shape(ABC): 
    def __init__(self):
        pass
    #create abstract method area()
    def area(self):
        pass

class Rectangle(type_shape):
  length = 6
  breadth = 4
  def area(self):
      return self.length*self.breadth

class Circle(type_shape):
  radius = 7
  def area(self):
      return 3.14*self.radius**2
class Square(type_shape):
  length = 4
  def area(self):
      return 4*self.length

class triangle:
  length = 5
  width = 4
  def area(self):
      return 0.5*self.length*self.width
r=Rectangle()
c=Circle()
s = Square() # object created for the class 'Square'
t = triangle() # object created for the class 'triangle'
print("Area of a rectangle:", r.area()) # call to 'area' method defined inside the class.
print("Area of a circle:", c.area()) # call to 'area' method defined inside the class.
print("Area of a square:", s.area()) # call to 'area' method defined inside the class.
print("Area of a triangle:", t.area()) # call to 'area' method defined inside the class.
```

## Output
<img width="1383" height="924" alt="image" src="https://github.com/user-attachments/assets/2bdfc7f0-25f4-4a54-95c0-de0899444128" />

## Result
Thus the python program to create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle` is completed successfully.
