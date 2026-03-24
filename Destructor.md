# Exp.No:22  
## Destructor

---

### AIM  
To create a Python class `Student` with a destructor.

---

### ALGORITHM

1. Begin the program.  
2. Define the `student` class.  
3. Inside the `student` class, define the `__init__` method (constructor) and the `__del__` method (destructor).  
4. Create an object `s2` of the `student` class. When the object `s2` is created, the `__init__` method is called, and its print statements are executed.  
5. Use the `del` statement to delete the object `s2`. This triggers the `__del__` method (destructor), and the respective print statements are executed.  
6. Terminate the program.

---

### PROGRAM

```
#Reg.no 212222060279
#Name Thiyaga Sri Charumathy
class Student:

    # constructor
    def __init__(self, name):
        print('Inside Constructor')
        self.name = name
        print('Object initialized')

    def show(self):
        print('Hello, my name is', self.name)
    def __del__(self):
        print("Inside destructor\nObject destroyed")
# create object
s1 = Student('Emma')
s1.show()

# delete object
del s1

```

### OUTPUT
<img width="646" height="246" alt="image" src="https://github.com/user-attachments/assets/589d5e69-0ed8-4ff0-bb89-7c5faf5bea11" />

### RESULT
Thus Add the destructor in the following python code to delete the instance of the class has been successfully implemented.
