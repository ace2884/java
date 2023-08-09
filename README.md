
1. **Define OOP concepts**:
   Object-Oriented Programming (OOP) is a programming paradigm based on the concept of "objects," which are instances of classes. OOP emphasizes the organization of code into classes and objects, enabling the modeling of real-world entities and their interactions. Key OOP concepts include:
   - **Class**: A blueprint or template that defines the structure and behavior of objects.
   - **Object**: An instance of a class, representing a real-world entity and encapsulating data and behavior.
   - **Encapsulation**: The bundling of data (attributes) and methods (functions) that operate on the data into a single unit (object).
   - **Inheritance**: A mechanism that allows a new class (subclass/derived class) to inherit properties and behaviors from an existing class (superclass/base class).
   - **Polymorphism**: The ability for objects of different classes to be treated as objects of a common superclass through method overriding and dynamic method dispatch.

2. **Distinguish between procedural language and OOPs**:
   Procedural languages focus on procedures and functions, where code is organized around procedures that operate on data. Examples include C and Pascal. OOP, on the other hand, is based on objects, where code is organized around classes and objects, promoting encapsulation, inheritance, and polymorphism. Examples of OOP languages are Java, Python, and C++.

3. **Differentiate between class and object**:
   A class is a blueprint or template that defines the structure and behavior of objects. It's like a blueprint for creating objects with specific attributes and methods. An object is an instance of a class, representing a specific entity with its own unique data and behavior. In simple terms, a class is a design, while an object is an instance based on that design.

4. **What is meant by ad-hoc polymorphism and pure polymorphism?**:
   - **Ad-hoc Polymorphism**: Also known as function overloading or operator overloading, this refers to the ability to define multiple methods with the same name but different parameter types or numbers. The appropriate method is selected based on the arguments passed during the call.
   - **Pure Polymorphism**: Also known as method overriding, this involves defining methods in subclasses with the same signature as methods in the superclass. This allows the subclass to provide its own implementation while adhering to a common interface defined by the superclass.

5. **List advantages of OOP and disadvantages of OOP**:
   Advantages:
   - Encapsulation: Helps maintain code organization and reduces complexity.
   - Reusability: Classes and objects can be reused in different parts of the program.
   - Flexibility: Supports easy modification and extension of code.
   - Modularity: Allows development and maintenance of code in smaller, manageable units.
   Disadvantages:
   - Learning Curve: OOP concepts might be initially complex for beginners.
   - Overhead: OOP programs can be larger and slower due to encapsulation and inheritance mechanisms.
   - Design Complexity: Poorly designed class hierarchies can lead to confusion and complexity.

6. **Write history of Java**:
   Java was developed by James Gosling and his team at Sun Microsystems in the mid-1990s. It was initially intended for use in consumer electronics and appliances. Java's "write once, run anywhere" capability was a significant breakthrough. In 1995, Java 1.0 was released to the public. Over the years, Java evolved with various updates and additions. Sun Microsystems was later acquired by Oracle Corporation, which continued to manage Java. Java's popularity grew due to its platform independence, robustness, and versatility.

7. **What is the significance of Java’s byte code?**:
   Java's bytecode is an intermediate representation of the source code that is generated during compilation. It allows Java programs to be platform-independent. Bytecode can be executed by the Java Virtual Machine (JVM) on any platform, making Java programs portable without needing to recompile them for each platform.

8. **What is JVM, JDK, JRE, and JIT**:
   - **JVM (Java Virtual Machine)**: It's a runtime environment that executes Java bytecode. It provides platform independence by interpreting or compiling bytecode into machine code.
   - **JDK (Java Development Kit)**: It's a software development kit that includes tools, libraries, and the Java compiler for creating, compiling, and running Java applications.
   - **JRE (Java Runtime Environment)**: It's the runtime environment that includes the JVM and necessary libraries to run compiled Java applications.
   - **JIT (Just-In-Time Compiler)**: Part of the JVM, it compiles bytecode into native machine code at runtime for faster execution.

9. **Describe a data type and its type and range**:
   A data type defines the kind of data a variable can hold. In Java, there are two main categories of data types:
   - **Primitive Data Types**: These are basic data types that store single values. Examples include `int` (integer), `double` (floating-point), `char` (character), `boolean` (true/false).
   - **Reference Data Types**: These refer to objects or instances of classes. Examples include user-defined classes, arrays, and interfaces.

10. **Differentiate between print() and println() methods in Java**:
    - `print()`: This method prints the specified content to the console without moving the cursor to the next line.
    - `println()`: This method prints the specified content to the console and then moves the cursor to the next line.

11. **What are symbolic constants in Java? Explain with examples**:
    Symbolic constants, also known as named constants or constants, are variables whose values cannot be changed once they are assigned. They are often used to define values that are used throughout the program without repeating literals. For example:
    ```java
    final double PI = 3.14159;
    final int MAX_ATTEMPTS = 5;
    ```

12. **Describe a constant**:
    A constant is a value that remains unchanged throughout the execution of a program. In Java, constants are typically declared using the `final` keyword. They provide meaningful names to values and improve code readability.

13. **Describe scope and lifetime of variables**:
    - **Scope**: The scope of a variable refers to the region of the code where the variable can be accessed and used. It defines the visibility and accessibility of the variable. Variables can have block scope, method scope, class scope, etc.
    - **Lifetime**: The lifetime of a variable is the duration during which the variable exists in memory and retains its value. It begins when the variable is created and ends when it goes out of scope or when the program execution completes.

14. **List types of operators in Java**:
    - Arithmetic Operators: `+`, `-`, `*`, `/`, `%`
    - Relational Operators: `==`, `!=`, `>`, `<`, `>=`, `<=`
    - Logical Operators: `&&`, `||`, `!`
    - Assignment Operators: `=`, `+=`, `-=`, `*=`, `/=`, `%=`, `&=`, `|=`, `^=`, `<<=`, `>>=`, `>>>=`
    - Unary Operators: `+`, `-`, `

++`, `--`, `!`
    - Bitwise Operators: `&`, `|`, `^`, `~`, `<<`, `>>`, `>>>`, etc.

15. **Define type conversion in Java**:
    Type conversion, also known as type casting, refers to the process of converting a value from one data type to another. There are two types of type conversion: implicit (automatic) and explicit (manual).

16. **Define type casting in Java? With an example**:
    Type casting is the process of explicitly converting a value from one data type to another. For example:
    ```java
    double num1 = 3.14;
    int num2 = (int) num1; // Explicitly casting double to int
    ```

17. **Explain the use of ‘for’ and 'for each' statements in Java with an example**:
    - `for` Loop: It's used for iterating a certain number of times. Syntax: `for (initialization; condition; increment/decrement) { /* loop body */ }`
    - `for each` Loop: It's used for iterating over elements in an array or collection. Syntax: `for (data_type element : array/collection) { /* loop body */ }`
    ```java
    // for loop example
    for (int i = 1; i <= 5; i++) {
        System.out.println(i);
    }

    // for each loop example
    int[] numbers = { 1, 2, 3, 4, 5 };
    for (int num : numbers) {
        System.out.println(num);
    }
    ```

18. **Define enumerated types in Java**:
    Enumerated types (enums) are a special data type that represents a set of named constant values. Enums improve code readability and type safety by providing a way to define a set of possible values for a variable.
    ```java
    enum Day {
        MONDAY, TUESDAY, WEDNESDAY, THURSDAY, FRIDAY, SATURDAY, SUNDAY
    }
    Day today = Day.WEDNESDAY;
    ```

19. **Define an array and its types in Java**:
    An array is a data structure that can store a fixed-size collection of elements of the same data type. There are single-dimensional arrays, multidimensional arrays, and dynamic arrays (ArrayLists).
    ```java
    int[] numbers = { 1, 2, 3, 4, 5 }; // Single-dimensional array
    int[][] matrix = { { 1, 2 }, { 3, 4 } }; // Multidimensional array
    ```

20. **Define 'this' reference**:
    The `this` reference in Java refers to the current instance of the class. It's used to differentiate between instance variables and method parameters that have the same name. It can also be used to call constructors within constructors.

21. **Define constructor in Java**:
    A constructor is a special method in a class that is used to initialize the object's state when it's created. It has the same name as the class and doesn't have a return type.
    ```java
    class Person {
        String name;

        // Constructor
        public Person(String name) {
            this.name = name;
        }
    }
    ```

22. **Define recursion in Java**:
    Recursion is a programming technique where a function calls itself in order to solve a problem. It's particularly useful for solving problems that can be broken down into smaller subproblems of the same type.

23. **Define garbage collection in Java**:
    Garbage collection is an automatic process in Java that identifies and removes objects that are no longer reachable and are thus no longer needed by the program. This helps in managing memory efficiently and prevents memory leaks.
    
    ***unit 2***


1. **Define Inheritance? List types of inheritances in Java**:
   Inheritance is a fundamental concept in object-oriented programming where a new class (subclass or derived class) is created by inheriting properties and behaviors from an existing class (superclass or base class). It promotes code reuse and supports the "is-a" relationship between classes.
   
   Types of inheritances in Java:
   - **Single Inheritance**: A subclass extends a single superclass.
   - **Multiple Inheritance (Interface Inheritance)**: A subclass implements multiple interfaces. (Java achieves this using interfaces)
   - **Multilevel Inheritance**: A class is derived from another class, which is itself derived from another class.
   - **Hierarchical Inheritance**: Multiple classes extend a single superclass.
   - **Hybrid Inheritance**: A combination of multiple and multilevel inheritance.

2. **Write about Member access rules**:
   In Java, there are four access modifiers that control the visibility and accessibility of class members (fields and methods):
   - **`public`**: Members can be accessed from anywhere.
   - **`protected`**: Members can be accessed within the same package or by subclasses.
   - **`default` (no modifier)**: Members can be accessed within the same package.
   - **`private`**: Members can be accessed only within the same class.

3. **Write Uses of 'Super' keyword**:
   The `super` keyword in Java is used to refer to the superclass's members (fields or methods) from within a subclass. It's used to resolve ambiguity, call superclass constructors, and access overridden methods.

4. **Write using 'final' keyword with inheritance**:
   When a class is marked as `final`, it cannot be inherited, meaning it can't be used as a superclass. If you declare a class as `final`, it indicates that you don't want it to have any subclasses.

5. **What is the difference between final, finally, and finalize keywords in Java**:
   - `final`: It's a keyword used to indicate that a variable, method, or class cannot be changed or overridden.
   - `finally`: It's a code block used in try-catch-finally to ensure that certain code is executed regardless of exceptions being thrown or not.
   - `finalize`: It's a method in the `Object` class that's called by the garbage collector before an object is deallocated. It's used to perform cleanup operations.

6. **Explain about Object class**:
   The `Object` class is the root class of all Java classes. Every class in Java is either directly or indirectly derived from the `Object` class. It provides basic methods such as `equals()`, `hashCode()`, `toString()`, and `getClass()`, which can be overridden in subclasses.

7. **Define abstract classes**:
   An abstract class is a class that cannot be instantiated and is meant to be subclassed. It may contain abstract methods (methods without implementation) that must be overridden by its subclasses. Abstract classes can also have concrete methods with implementation.

8. **Differences between method overloading and method overriding**:
   - **Method Overloading**: Involves defining multiple methods in the same class with the same name but different parameters. The methods must have different parameter lists (number or types of parameters).
   - **Method Overriding**: Occurs when a subclass provides a specific implementation for a method that is already defined in its superclass. The method signature (name and parameter list) must be the same in both classes.

9. **Difference between class, abstract class, and interface**:
   - **Class**: A blueprint that can be instantiated into objects. It can have fields, methods, constructors, etc.
   - **Abstract Class**: A class that cannot be instantiated and may contain abstract methods. It's meant to be subclassed.
   - **Interface**: A reference type that defines a contract for its implementers. It only contains abstract methods and constant fields.

10. **Define inner class**:
    An inner class is a class that is defined within another class. It has access to the members (fields and methods) of the outer class and can be used for various purposes like encapsulation and organization.

11. **List out the inner classes**:
    There are four types of inner classes in Java:
    - **Member Inner Class**: Defined at the member level of a class.
    - **Static Nested Class**: Similar to a member inner class but declared as static.
    - **Local Inner Class**: Defined within a block of code, like a method.
    - **Anonymous Inner Class**: A special case of a local inner class without a name.

12. **What is method overriding**:
    Method overriding is the process of defining a method in a subclass with the same name, return type, and parameters as a method in its superclass. The overridden method in the subclass provides a specific implementation while adhering to the same method signature.

13. **What is an interface**:
    An interface in Java is a reference type that defines a contract for its implementers. It only contains abstract methods (methods without a body) and constant fields. Implementing an interface requires a class to provide concrete implementations for the interface's methods.

14. **What is a package**:
    A package in Java is a way to organize related classes and interfaces into a hierarchical structure. It helps avoid naming conflicts and provides a systematic way to manage and group related code elements.

15. **Which keyword is used to import a package**:
    The `import` keyword is used to import a package in Java. It allows you to access classes and other members from the imported package without using their fully qualified names.
