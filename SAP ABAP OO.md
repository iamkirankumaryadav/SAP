# ABAP OO (Object-Oriented ABAP)  
- A programming paradigm that allows developers to structure their code in a more modular, reusable, and maintainable way.
- It introduces concepts like **classes**, **objects**, **inheritance**, **polymorphism**, and **encapsulation** to the ABAP language.

### Key Concepts in ABAP OO

1. **Class:**
- A **blueprint/prototype** for declaring and creating **objects**.
- Defines the **attributes/properties/variables** (data) and **methods/actions** (functions) that objects of that class will have.
- **Methods:** A function defined inside a class.
- Example: Person (Class): Attributes(Name, Age, Gender, Role) and Method (Walk(), Eat(), Sleep(), Work())

```python
class Vehicle:
    # Constructor Function:
    def __init__(self, name=''):
        self.name = name

bike = Vehicle()

# Here, __init__() is the constructor function that is called whenever a new object of that class is instantiated.
```

2. **Object:**
- An instance of a class. Allows programmers to use variables and methods defined inside the class.

```python
objectName = className()
```

3. **Inheritance:**
- Allows a new class to inherit properties and behaviours from an existing class.
- The newly created class is known as the **subclass** (child or derived class)
- The existing class from which the child class inherits is known as the **superclass** (parent or base class)
- Subclasses can extend or override the behaviour of their parent classes.

4. **Polymorphism:**
- The ability of objects to exist in many forms.
- Some functions are compatible with multiple data types. e.g. len() can be used for str, list, and dict.
- Enables code to be more flexible and reusable.
- Can be achieved through method overloading and overriding.

5. **Encapsulation:**
- Encapsulation binds the data (attributes) and the methods together into a single unit (class).
- Protects the data from unauthorized access and modification.
- Promotes modularity and code reusability.

6. **Method Overriding**
- The child classes in Python inherit methods and attributes from the parent class.
- We can redefine certain methods and attributes specifically to fit the child's class.

7. **Method Overloading (Not possible in Python)** 
- A way to create multiple methods with the same name but different arguments.

### Benefits of ABAP OO
- **Improved Code Reusability:** By creating reusable classes and objects, developers can reduce code duplication and maintenance effort.
- **Enhanced Code Maintainability:** Well-structured, modular code is easier to understand, modify, and debug.
- **Increased Flexibility:** Object-oriented design allows for flexible and extensible applications.
- **Better Code Quality:** Encapsulation and inheritance help to promote good programming practices and reduce errors.

### Using ABAP OO in SAP
- ABAP OO is widely used in SAP development, especially in the context of SAP Fiori applications and custom developments.
- It is often used to create reusable business objects, implement complex business logic, and build user interfaces.
- By adopting ABAP OO principles, developers can create more efficient, maintainable, and scalable SAP applications.
