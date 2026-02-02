
<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="120" />
</p>

## 📜 History of Java

- **James Gosling** is the father of Java, and it was introduced in **1991**.
- The software was initially named **GreenTalk**, and the team that developed it was called the **Green Team**.
- Later, the software was renamed to **Oak**. Oak is a symbol of strength and is a national tree of Germany.
- Since there was already an existing company named **Oak Technologies**, legal issues arose. Due to this, the software name was changed from **Oak to Java**.
- James Gosling and his team once went for coffee on an island where the coffee shop was named **Java**. Hence, they named the software **Java**, and the **coffee cup** was chosen as the logo.
- Java is a **high-level programming language** originally developed by **Sun Microsystems** and released in **1995**.
- Java runs on various platforms such as **Windows, macOS, and different versions of UNIX**.

---

## 🧩 Tokens in Java

**Token** is the smallest unit of a Java program.

### Types of Tokens in Java:

1. Identifier  
2. Keywords  
3. Literals  
4. Operators  
5. Separators  
6. Comments  

---

## 1️⃣ Identifier

An **Identifier** is a name given to a Java program elements such as:
- Class name
- Method name
- Variable name

---

## 2️⃣ Keywords

**Keywords** are **pre-defined words** in Java that have a fixed meaning.

- Java contains **50 reserved keywords**
- Keywords cannot be used as identifiers

Example keywords:

## 🔑 Java Keywords (50)

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

---

### 2️⃣ Character Literals
- Enclosed within **single quotes (`' '`)**
- Represent a single character

Examples:
'A', '5', '$', ' '

## 4. Operators in Java

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

---

## 5. Separators

Separators are used to separate the given code.

In Java, separators are:

- `{ }` → Braces  
- `[ ]` → Brackets  
- `( )` → Parentheses  
- `;` → Semicolon  
- `,` → Comma  

---

## 6. Comments

Comments are used to provide additional information for the Java program.

### Types of comments in Java

1️⃣ **Single line comments**

// This is a single line comment

2️⃣ Block comments

/* This is a block comment */

Java Program Execution Flow

• We write the program using EditPlus / Notepad.
• This program is called Source Code.
• Source code is written in a human-readable format.

• To convert human-readable code into machine-readable code, we use the Command Prompt.
• Two main operations are performed:
  1. javac (Java Compiler)
  2. java (Java Interpreter)

• After writing the program, save the file with the .java extension.
• Save the file in the following path:
  C:/Program Files/Java/JDK1.8/bin

• The .java file is given as input to the compiler.
• The compiler performs the following checks:
  1. Syntax checking
  2. Rule validation
  3. Translation from .java file to .class file

• If any syntax or rule violation occurs, a Compile Time Error is generated.
• If there are no errors, a .class file is generated.

• The .class file is an Intermediate Code.
• It is in Byte Code format.
• Byte code is not understandable by humans or machines directly.

• The .class file is given as input to the Java Interpreter.
• The interpreter performs the following actions:
  1. Reads the code line by line
  2. Executes the program using JVM
  3. Translates byte code into binary language

• If abnormal statements are found (example: 1/0),
  Java throws a Run Time Error.
• Example of runtime error: ArithmeticException.

Java Components

JIT (Just In Time Compiler)
• Responsible for converting .class file into binary format.

JVM (Java Virtual Machine)
• Responsible for executing the Java program.

JRE (Java Runtime Environment)
• Provides the environment required to run Java programs.

JDK (Java Development Kit)
• Contains all libraries and development tools required to build Java applications.

• All Java programs execute from left to right.
• Execution also follows top to bottom order.

