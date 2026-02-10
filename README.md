
<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="120" />
</p>

## History of Java

- **James Gosling** is the father of Java, and it was introduced in **1991**.
- The software was initially named **GreenTalk**, and the team that developed it was called the **Green Team**.
- Later, the software was renamed to **Oak**. Oak is a symbol of strength and is a national tree of Germany.
- Since there was already an existing company named **Oak Technologies**, legal issues arose. Due to this, the software name was changed from **Oak to Java**.
- James Gosling and his team once went for coffee on an island where the coffee shop was named **Java**. Hence, they named the software **Java**, and the **coffee cup** was chosen as the logo.
- Java is a **high-level programming language** originally developed by **Sun Microsystems** and released in **1995**.
- Java runs on various platforms such as **Windows, macOS, and different versions of UNIX**.


## Tokens in Java

**Token** is the smallest unit of a Java program.

### Types of Tokens in Java:

1. Identifier  
2. Keywords  
3. Literals  
4. Operators  
5. Separators  
6. Comments  


## 1️⃣ Identifier

An **Identifier** is a name given to a Java program elements such as:
- Class name
- Method name
- Variable name


## 2️⃣ Keywords

**Keywords** are **pre-defined words** in Java that have a fixed meaning.

- Java contains **50 reserved keywords**
- Keywords cannot be used as identifiers


##  Java Keywords (50)

| S.No | Keyword | S.No | Keyword |
|-----:|--------|-----:|--------|
| 1 | abstract | 26 | instanceof |
| 2 | assert | 27 | int |
| 3 | boolean | 28 | interface |
| 4 | break | 29 | long |
| 5 | byte | 30 | native |
| 6 | case | 31 | new |
| 7 | catch | 32 | package |
| 8 | char | 33 | private |
| 9 | class | 34 | protected |
|10 | const | 35 | public |
|11 | continue | 36 | return |
|12 | default | 37 | short |
|13 | do | 38 | static |
|14 | double | 39 | strictfp |
|15 | else | 40 | super |
|16 | enum | 41 | switch |
|17 | extends | 42 | synchronized |
|18 | final | 43 | this |
|19 | finally | 44 | throw |
|20 | float | 45 | throws |
|21 | for | 46 | transient |
|22 | goto | 47 | try |
|23 | if | 48 | void |
|24 | implements | 49 | volatile |
|25 | import | 50 | while |

## 3️⃣ Literals in Java

**Literals** are fixed values that are used directly in Java programs.

### Types of Literals in Java

### 1️⃣ Number Literals
Used to represent numeric values.

- **Integer Literals**  
  Examples: `9`, `8`, `7`, `6`, `5`

- **Decimal (Floating-Point) Literals**  
  Examples: `0.55`, `0.75`


### 2️⃣ Character Literals
- Enclosed within **single quotes (`' '`)**
- Represent a single character

Examples:
'A', '5', '$', ' '

## 4️⃣ Operators in Java

Operators are symbols used to perform operations on operands.

### Operator Types and Categories

| Operator Type | Category           | Operators                          |
|---------------|------------------|-----------------------------------|
| UNARY         | Postfix           | `expr++`, `expr--`                |
| UNARY         | Prefix            | `++expr`, `--expr`, `+expr`, `-expr`, `!expr` |
| ARITHMETIC    | Multiplicative    | `*`, `/`, `%`                     |
| ARITHMETIC    | Additive          | `+`, `-`                          |
| SHIFT         | Shift             | `<<`, `>>`, `>>>`                 |
| RELATIONAL    | Comparison        | `<`, `>`, `<=`, `>=`, `instanceof` |
| RELATIONAL    | Equality          | `==`, `!=`                        |
| BITWISE       | Bitwise AND       | `&`                               |
| BITWISE       | Bitwise Exclusive OR | `^`                            |
| BITWISE       | Bitwise Inclusive OR | `|`                             |
| LOGICAL       | Logical AND       | `&&`                              |
| LOGICAL       | Logical OR        | `||`                              |
| TERNARY       | Ternary           | `? :`                             |
| ASSIGNMENT    | Assignment        | `=`, `+=`, `-=`, `*=`, `/=`, `%=`|
| ASSIGNMENT    | Assignment        | `&=`, `^=`, `<<=`, `>>=`, `>>>=` |


## 5️⃣ Separators

Separators are used to separate the given code.

In Java, separators are:

- `{ }` → Braces  
- `[ ]` → Brackets  
- `( )` → Parentheses  
- `;` → Semicolon  
- `,` → Comma  


## 6️⃣ Comments

Comments are used to provide additional information for the Java program.

### Types of comments in Java

1️⃣ **Single line comments**

    // This is a single line comment

2️⃣ **Block comments**

    /* This is a block comment */

## Java Architecture



![image](https://github.com/nirmaltej2003/Java-Skill-Up/blob/main/Screenshot%202026-02-07%20084548.png)

- We write the program using EditPlus / Notepad.
- This program is called **Source Code**.
- Source code is written in a human-readable format.

- To convert human-readable code into machine-readable code, we use the **Command Prompt**.
- Two main operations are performed:
  1. javac (Java Compiler)
  2. java (Java Interpreter)

- After writing the program, save the file with the `.java` extension.
- Save the file in the following path:
  
  C:/Program Files/Java/JDK1.8/bin

- The `.java` file is given as input to the compiler.
- The compiler performs the following checks:
  1. Syntax checking
  2. Rule validation
  3. Translation from `.java` file to `.class` file

- If any syntax or rule violation occurs, a **Compile Time Error** is generated.
- If there are no errors, a `.class` file is generated.

- The `.class` file is an **Intermediate Code**.
- It is in **Byte Code** format.
- Byte code is not understandable by humans or machines directly.

- The `.class` file is given as input to the Java Interpreter.
- The interpreter performs the following actions:
  1. Reads the code line by line
  2. Executes the program using JVM
  3. Translates byte code into binary language

- If abnormal statements are found (example: `1/0`),
  Java throws a **Run Time Error**.
- Example of runtime error: `ArithmeticException`.

## Java Components



![image](https://github.com/nirmaltej2003/Java-Skill-Up/blob/main/Screenshot%202026-02-08%20110633.png)

JIT (Just In Time Compiler)
- Responsible for converting `.class` file into binary format.

JVM (Java Virtual Machine)
- Responsible for executing the Java program.

JRE (Java Runtime Environment)
- Provides the environment required to run Java programs.

JDK (Java Development Kit)
- Contains all libraries and development tools required to build Java applications.
  
##  JAVA

Java is a programming language used to develop software applications.  
It is an Object-Oriented Programming (OOP) language.

##  Java Features

- Secure language  
- Robust  
- Platform independent  
- High performance  
- Compiled and interpreted  
- Multithreaded  
- Object-oriented  
- Polyglot (programs written using Java syntax can interoperate with other languages)

## Types in Java


**Java has four types:**

1. Class  
2. Interface  
3. Enum  
4. Annotation  


## 1️⃣ Class

A class is a blueprint or template used to create objects.

### Example: Program to print "Hello Java"

    
    class Sample {
        public static void main(String[] args) {
            System.out.println("Hello Java");
        }
    }
-----------------------------------------
**Compilation Syntax**

    javac filename.java


Example:

    javac Sample.java

**Interpretation Syntax**

    java filename


Example:

    java Sample

## Variables


A variable is a named memory location used to store data.  
The value of a variable can change multiple times during execution.

## Types of Variables


1️⃣ **Primitive Data Types**

- byte  
- short  
- int  
- long  
- float  
- double  
- char  
- boolean  

2️⃣  **Non-Primitive Data Types**

- Arrays  
- String  
- Any class type
  
--------------------------------
a) **Variable Declaration**

    datatype variableName;


Example:

    int a;

b) **Variable Initialization**

    variableName = value;


Example:

    a = 10;

c) **Variable Utilization**

    System.out.println(a);


Output:

    10

d) **Declaration and Initialization in a Single Line**

    int a = 10;

e) **Variable Re-initialization**

    int y = 80;
    y = 100;
    System.out.println(y);


Output:

    100

f) **Copying Value from One Variable to Another**

    int a = 20;
    int b = a;
    
    System.out.println(a);
    System.out.println(b);


Output:

    20
    20

## Classification of Variables


1️⃣ **Local Variables**

- Declared inside a method  
- Scope is limited to the method  
- Cannot be static or non-static  
- Do not have default values  
- Must be initialized before use  


Example:

    class Sample {
        public static void main(String[] args) {
            int x = 20;
            System.out.println(x);
        }
    }


2️⃣ **Global Variables (Class Variables)**


- Declared outside methods and inside a class  
- Scope is throughout the class  
- Can be static or non-static  
- Have default values  
- Cannot be re-initialized directly outside methods  


Example:

    class Sample {
        static int a = 20;
    
        public static void main(String[] args) {
            System.out.println(a);
        }
    }


 ## Methods

A method is a block of statements which gets executed whenever it is
called or invoked.

a) General Syntax

    {access_specifier}  {modifier}  {return_type}  {method_name(arguments)}


b) Access Specifiers

- public
- private
- protected
- default (package-level)


c) Modifiers

- static
- non-static


d) Return Types

- void
- int
- double
- char
- String
- float
- boolean
- class type


e) Method Name

- Identifier


f) Arguments / Parameters

- char
- String
- float
- boolean
- class type

[ Arguments are optional ]


## Final Variable

Any variable declared using the keyword final is called a final variable.
The value of a final variable cannot be changed.

Example: Method Without Parameters
--------------------------------------------------
    class Circle {
        static void area() {
            final double pi = 3.142;
            int r = 4;
            double result = pi * r * r;
            System.out.println(result);
        }
    
        public static void main(String[] args) {
            area();
        }
    }

Method with Parameters
--------------------------------------------------
Whenever we want to give input to a method, we use a method with parameters.

  Example:
  
    class Circle {
        static void area(int r) {
            final double pi = 3.142;
            double result = pi * r * r;
            System.out.println(result);
        }
    
        public static void main(String[] args) {
            area(6);
        }
    }

Method with Return Type
--------------------------------------------------
Whenever we want to use the result for further operations,
we use a method with a return type.

Example:

    class Circle {
        static double area() {
            int r = 5;
            final double pi = 3.142;
            double result = pi * r * r;
            return result;
        }
        public static void main(String[] args) {
            double x = area();
            System.out.println("Area is " + x);
        }
    }


## Conditional Statements


To check for logical conditions, we use conditional statements.


1️⃣ **If condition**

Syntax:

    if (condition)
    {
        statements;
    }

Example:

    class Demo {
        public static void main(String[] args) {
            if (5 > 3) {
                System.out.println("hi");
            }
        }
    }



2️⃣ **If – else condition**

Syntax:

    if (condition)
    {
        statements;
    }
    else
    {
        statements;
    }

Example:

    class Demo {
        public static void main(String[] args) {
            if (5 > 30) {
                System.out.println("hi");
            } else {
                System.out.println("hello");
            }
        }
    }



3️⃣ **Else – if condition**

Syntax:

    if (condition)
    {
        statements;
    }
    else if (condition)
    {
        statements;
    }
    else
    {
        statements;
    }

Example:

    class Demo {
        public static void main(String[] args) {
            if (5 > 30) {
                System.out.println("hi");
            } else if (5 > 2) {
                System.out.println("hello");
            } else {
                System.out.println("cool");
            }
        }
    }



4️⃣ **Nested if – else condition**

Syntax:

    if (condition)
    {
        if (condition)
        {
            statements;
        }
        else
        {
            statements;
        }
    }
    else
    {
        statements;
    }


## Loops


**For Loop**

Syntax:

    for (initialization; condition; increment/decrement)
    {
        statements;
    }



Example 1️⃣:
    
    for (int i = 1; i <= 4; i++) {
        System.out.println("cool");
    }
    // Output: cool, cool, cool, cool



Example 2️⃣:

    for (int i = 1; i <= 10; i++) {
        System.out.println(i);
    }
    // Output: 1 2 3 4 5 6 7 8 9 10



Example 3️⃣:

    for (int i = 10; i >= 1; i--) {
        System.out.println(i);
    }
    // Output: 10 9 8 7 6 5 4 3 2 1



Example 4️⃣: Without using semicolon inside the loop body

    for (int i = 1; i <= n; System.out.println(i)) {
        i++;
    }

## Switch Case Statement


- Switch case is used for pattern matching.
- The particular case will be executed based on the input value.

Example:

    class Demo {
        public static void main(String[] args) {
    
            int input = 3;
    
            switch (input) {
                case 1:
                    System.out.println("FCD");
                    break;
    
                case 2:
                    System.out.println("FC");
                    break;
    
                default:
                    System.out.println("Invalid input");
                    break;
            }
        }
    }

## STATIC

➢ Any member of the class declared with a keyword static is called as static
member of the class.

➢ Static is always associated with class.

➢ Static is one copy.

➢ All the static members will be stored in static pool area.

➢ Whenever we want to access static members from one class to another class
then we should use
Class_name.variable_name();
or
Class_name.method_name();

Note:

➢ We can develop multiple classes in a single file.

➢ Whichever class is having main method that class file should be filename.

➢ For each and every class present in the file will have corresponding .class
file.

Ex: B / W the classes with a method as static

    class Circle 
    {
      static void area() 
      {
        final double pi = 3.142;
        int r = 5;
        double result = pi * r * r;
        System.out.println("result is " + result);
      }
    }
    class Tester 
    {
      public static void main(String[] args) 
      {
      Circle.area();
      }
    }

Ex: B / W the classes with a method as static with parameter

    class Circle 
    {
      static void area(int r) 
      {
        final double pi = 3.142;
        double result = pi * r * r;
        System.out.println("result is " + result);
      }
    }
    class Tester 
    {
      public static void main(String[] args) 
      {
      Circle.area(5);
      }
    }

Ex: B / W the classes with a method as static with return type

    class Circle 
    {
      static double area() 
      {
        int r = 5;
        final double pi = 3.142;
        double result = pi * r * r;
        return result;
      }
    }
    class Tester 
    {
      public static void main(String[] args) 
      {
      double x = Circle.area();
      System.out.println("area is " + x);
      }
    }

## NON – STATIC

➢ Any member of the class declared without a keyword static is called as
Non-static member of the class.

➢ Non-static is always associated with object.

➢ Non-static is multiple copy.

➢ All the Non-static members will be stored in Heap memory.

➢ Whenever we want to access Non-static members then we should use

Object.variable_name

or

Object.method_name

Reference variable.variable_name

or

Reference variable.method_name

Syntax:

    new Class_name();

Ex:

new Sample(); → object

➢ new operator will create random memory space into the heap memory.

➢ Constructor will initialize all the non-static members into the heap memory.

## JVM MEMORY

![image](https://github.com/nirmaltej2003/Java-Skill-Up/blob/main/Screenshot%202026-02-08%20111044.png)

➢ Whenever class loader loads the class all the static members will get
initialized in the static pool area.

➢ JVM starts executing from main method in the program.

➢ The first statement is the object creation.

➢ Equal operator works from right to left.

➢ New operator will create a random memory space in the heap memory.

➢ Constructor will initialize all the non-static members into the heap memory.

➢ While creating the object itself we pass the arguments which will get
initialized in the constructor and from constructor it will get initialized
to the object variables.

➢ Now in the main method the object address will be stored in the reference
variable and through that reference variable we access the values.

## JVM MEMORY PARTS

1️⃣ Stack
- Used for execution.
- Follows LIFO (Last In First Out).

2️⃣ Heap Memory
- Used to store non-static members.
- Non-static members are created when object is created.

3️⃣ Static Pool Area
- Used to store static members.
- Static members are initialized when class loader loads the class.

4️⃣ Method Area
- Used to store method body or definition.
- Both static and non-static method bodies are stored here.

## REFERENCE VARIABLE

A reference variable is a special type of variable used to store the address of an object.

A reference variable can hold:
- null
- object address


## Reference Variable Declaration

Syntax:    

    class_name reference_variable;

Example:

    int a;
    Tester t1;



## Reference Variable Initialization

Syntax:

    reference_variable = object;

Example:

    t1 = new Tester();


## Reference Variable Declaration and Initialization

Syntax:

    class_name reference_variable = object;

This is called homogeneous object creation.

Example:

    Tester t1 = new Tester();


## Non-Static to Static Using Reference Variable

    class Circle {
        void area() {
            final double pi = 3.142;
            int r = 4;
            double result = pi * r * r;
            System.out.println(result);
        }
    
        public static void main(String[] args) {
            Circle c1 = new Circle();
            c1.area();
        }
    }
    

Important Note:

Multiple objects can be stored in multiple reference variables.
Changes made to one object will not affect other objects.

Ref1  -> address -> object
Ref2  -> address -> object


## Example: Different Objects, Different Addresses

    class Demo1 {
        int a = 10;
    
        public static void main(String[] args) {
            Demo1 d1 = new Demo1();
            System.out.println(d1);
    
            Demo1 d2 = new Demo1();
            System.out.println(d2);
        }
    }

Output:

    Demo1@15db9742
    Demo1@06d69c


Note:

Whenever we print a reference variable, it prints the object address.

Fully Qualified Path Format:

package_name.class_name@hexadecimal_value

Example:

Demo1@1bcfc76


## Example: Same Object, Same Address

    class Demo1 {
        int a = 10;
    
        public static void main(String[] args) {
            Demo1 d1 = new Demo1();
            Demo1 d2 = d1;
    
            System.out.println(d1);
            System.out.println(d2);
        }
    }

Output:

    Demo1@15db9742
    Demo1@15db9742


## COMPOSITION / AGGREGATION

A class having an object of another class is called Composition.
It is also known as "Has-A Relationship".

## Example of Composition:

    class Tester {
        void add() {
            System.out.println("hii");
        }
    }
    
    class Sample {
        public static void main(String[] args) {
            Tester t1 = new Tester();
            t1.add();
        }
    }

# BLOCKS IN JAVA

Blocks are used to initialize variables and execute statements at specific times in a Java program.
There are two types of blocks in Java: Static Initialization Block (SIB) and Instance Initialization Block (IIB).

1️⃣ **Static Initialization Block (SIB):**

Any block which is declared using the keyword static is called a Static Initialization Block.

SIB is used to initialize static members.

SIB gets executed before the main method.

We can have multiple SIBs and they execute in sequential order.

Syntax:

    static {
        // statements
    }

Example:

    class Demo {
        static int a;
    
        static {
            a = 10;
        }
    
        public static void main(String[] args) {
            System.out.println(a);
        }
    }

Output:

    10

2️⃣ **Instance Initialization Block (IIB):**

Any block which is declared without the keyword static is called an Instance Initialization Block.

IIB is used to initialize non-static members.

IIB gets executed whenever an object is created.

We can have multiple IIBs and they execute in sequential order.

Syntax:

    {
        // statements
    }

Example:

    class Demo {
    
        {
            System.out.println("---- IIB ----");
        }
    
        public static void main(String[] args) {
            new Demo();
        }
    }

Output:

    ---- IIB -----

Execution Order:

1. Static Initialization Block
2. main() method starts
3. Instance Initialization Block
4. Constructor (if present)

Key Points:

SIB executes once when the class is loaded.
IIB executes every time an object is created.
Both blocks execute before the constructor.
Execution follows top-to-bottom order.

