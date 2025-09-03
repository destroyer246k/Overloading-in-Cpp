# Overloading-in-Cpp
**Aim:**    To study **constructor overloading**, **function overloading**, and **operator overloading** in C++.

**Tools:**      GNU g++ compiler for local compilation or any online C++ compiler.
# Theory  
In Object-Oriented Programming overloading is the use of the same name for a function, constructor or operator in such a way that the behavior of that name changes based on the input or context. It makes your code cleaner, simpler and easier to reuse. Instead of creating multiple function names to perform similar tasks. you can write one name and overload it with different definitions. This also makes the program easier to read and understand.

Having a single name that can adapt based on arguments or data types is a powerful feature of OOP. A constructor can take different types of inputs to create an object in multiple ways, and operators can be redefined so that your objects behave like built-in data types when used in mathematical expressions.
### **Types of Overloading**
- **Constructor Overloading** – When a class includes more than one constructor with a different number or types of parameters, allowing objects to be created in multiple ways. 
- **Function Overloading** – When a function name is reused with different parameter lists, and the choice of which to call is made by the compiler during compilation. 
- **Operator Overloading** – The redefinition of operators like `+`, `-`, `*`, and `/` for user-defined types, allowing objects to interact in an intuitive way. 
## **Program 1: Constructor Overloading (First Example)**  

### Logic:  
This program shows how multiple constructors can exist in one class. The class `Add` has three constructors, each with a different parameter list. When objects are created, the compiler automatically detects which constructor to use based on the arguments passed. For example, one constructor adds two integers, another adds two floating-point numbers, and the third one adds three integers.
## **Program 2: Constructor Overloading (Second Example)**  
### Logic:  
This program demonstrates constructor overloading using a `Product` class. One constructor calculates profit or loss when cost price, selling price, and quantity sold are given. Another constructor calculates the remaining inventory by subtracting the sold items from the total available stock. This shows how the same class can be used for two different tasks without writing separate functions.
### Algorithm:  
1. Start  
2. Define a class Product.  
3. Create one constructor to calculate profit or loss using cost price, selling price, and items sold.  
4. Create another constructor to calculate remaining stock from total available and sold quantity.  
5. In main, create objects with required parameters for both operations.  
6. Display results.  
7. End  
## **Program 3: Function Overloading**
### Logic:  
The `Shapes` class demonstrates function overloading by creating multiple functions with the same name `area` but different parameters. Depending on the arguments, it calculates the area of different shapes such as square, circle, rectangle, and triangle. This approach avoids writing multiple separate functions for each shape and keeps the code clean and easy to manage.
### Algorithm:  
1. Start  
2. Define a class Shapes.  
3. Write different versions of the area function:  
   - One for square area calculation.  
   - One for circle area calculation.  
   - One for rectangle area calculation.  
   - One for triangle area calculation.  
4. In main, create objects and call the area function with suitable arguments.  
5. Display the results.  
6. End  
## **Program 4: Operator Overloading (Complex Number Addition)**  
### Logic:  
This program demonstrates operator overloading by redefining the `+` operator for a `Complex` class. It allows complex numbers to be added naturally using the `c1 + c2` syntax. The overloaded `+` operator function adds the real parts and imaginary parts separately, returning a new object that holds the result. This makes complex number addition as simple and intuitive as adding normal integers or floats.
### Algorithm:  
1. Start  
2. Define a class Complex with members for real and imaginary parts.  
3. Write a constructor to initialize values.  
4. Overload the + operator to add two Complex objects.  
5. Create two Complex objects in main, add them using +, and display the result.  
6. End  
## **Program 5: Operator Overloading (Calculator)**  
### Logic:  
This program shows how arithmetic operators like `+`, `-`, `*`, and `/` can be overloaded for a `Calc` class. By overloading these operators, the objects can perform addition, subtraction, multiplication, and division just like primitive data types. This makes the interaction between objects simple, clean, and intuitive
### Algorithm:  
1. Start  
2. Define a class Calc with a member num.  
3. Overload +, -, *, and / operators to return results as new Calc objects.  
4. Create objects in main and perform all operations.  
5. Display the results.  
6. End  
# **Conclusion**  
Constructor overloading initializes objects in distinctive ways. Function overloading uses the same name for different purposes, making the code easier to read and maintain. Operator overloading allows an object to behave like a built-in type, providing a simple and natural way to perform operations while keeping them readable and clean. 
These techniques promote an effective programming style, making programs more flexible, cleaner, and more object-oriented.
