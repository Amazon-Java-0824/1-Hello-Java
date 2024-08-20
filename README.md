# 1 - Hello Java
![](coffee.png)
## Table of Contents

1. [Learning Objectives](#learning-objectives)
2. [Introduction to Programming and Java](#1-introduction-to-programming-and-java)
   - [What is Programming?](#what-is-programming)
   - [Introduction to Java](#introduction-to-java)
   - [Setting Up Your Workspace](#setting-up-your-workspace)
3. [Your First Program: Hello, World!](#2-your-first-program-hello-world)
4. [Variables and Data Types](#3-variables-and-data-types)
   - [Understanding Variables](#understanding-variables)
   - [Types of Variables in Java](#types-of-variables-in-java)
   - [Declaring and Using Variables](#declaring-and-using-variables)
   - [Why Variables are Important](#why-variables-are-important)
   - [Practice Exercise: Personal Library Catalog](#practice-exercise-personal-library-catalog-20-minutes)
5. [Basic Java Operators](#4-basic-java-operators)
   - [Arithmetic Operators](#1-arithmetic-operators)
   - [Assignment Operator](#2-assignment-operator)
   - [Compound Assignment Operators](#3-compound-assignment-operators)
   - [Comparison Operators](#4-comparison-operators)
   - [Logical Operators](#5-logical-operators)
   - [Practice with Operators](#practice-with-operators)
6. [Control Flow](#5-control-flow)
   - [If Statements](#if-statements)
   - [Practice Exercise: Grade Calculator](#practice-exercise-grade-calculator-15-minutes)
   - [Loops](#loops)
   - [Practice Exercise: Multiplication Table Generator](#practice-exercise-multiplication-table-generator-20-minutes)
7. [Arrays](#6-arrays)
   - [What is an Array?](#what-is-an-array)
   - [Declaring and Initializing Arrays](#declaring-and-initializing-arrays)
   - [Accessing Array Elements](#accessing-array-elements)
   - [Modifying Array Elements](#modifying-array-elements)
   - [Array Length](#array-length)
   - [Iterating Through Arrays](#iterating-through-arrays)
   - [Common Array Operations](#common-array-operations)
   - [Practice Exercise: Temperature Tracker](#practice-exercise-temperature-tracker-20-minutes)
8. [Working with Strings](#7-working-with-strings)
   - [Common String Methods](#common-string-methods)
   - [Important Note on String Immutability](#important-note-on-string-immutability)
   - [Practice Exercise: Name Analyzer](#practice-exercise-name-analyzer-20-minutes)
9. [Key Takeaways](#key-takeaways)
10. [Glossary of Key Terms](#glossary-of-key-terms)



### Learning Objectives
By the end of this lesson, you will be able to:
1. Understand basic programming concepts
2. Write and run simple Java programs
3. Use variables, data types, and operators in Java
4. Implement control flow using if statements and loops
5. Work with arrays and strings in Java

## 1. Introduction to Programming and Java

### What is Programming?
Programming is like giving instructions to a very literal friend to make a sandwich. You need to be precise and break down each step clearly.

### Introduction to Java
Java is like learning a new language, but instead of communicating with people, you're communicating with computers. Just like human languages have grammar rules, Java has syntax rules we need to follow.

### Setting Up Your Workspace
Before we start cooking (coding), we need to set up our kitchen (development environment):
1. Install Java Development Kit (JDK) - This is like getting your basic cooking utensils - Java 17.
2. Install an Integrated Development Environment (IDE) - Think of this as your specialized kitchen for coding. We recommend IntelliJ IDEA.

## 2. Your First Program: Hello, World!

Just like you might say "Hello" when learning a new language, in programming, we start with printing "Hello, World!". Here's how it looks:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

Don't worry if this looks confusing now. We'll break it down and explain each part as we progress through the course.

## 3. Variables and Data Types

### Understanding Variables
Variables are one of the most fundamental concepts in programming. Think of a variable as a container or a labeled box that holds a piece of information.

#### Real-World Analogy
Imagine you're organizing a party. You might use different containers to hold different items:
- A bowl for chips
- A pitcher for juice
- A plate for cookies

In programming, variables are like these containers. Each variable has:
1. A name (like "bowl", "pitcher", "plate")
2. A type (what kind of thing it can hold)
3. A value (the actual content)

### Types of Variables in Java
In Java, every variable has a specific type. Here are some basic types:

1. `int`: For whole numbers (e.g., 1, -5, 1000)
2. `double`: For decimal numbers (e.g., 3.14, -0.01, 2.0)
3. `boolean`: For true/false values
4. `char`: For single characters (e.g., 'A', '7', '$')
5. `String`: For text (e.g., "Hello, World!")

### Declaring and Using Variables
To create a variable in Java, you need to declare it. Here's the basic syntax:

```java
type variableName = value;
```

Examples:
```java
int age = 25;
double price = 19.99;
boolean isStudent = true;
char grade = 'A';
String name = "Alice";
```

### Why Variables are Important
1. **Reusability**: You can use the same value multiple times in your program.
2. **Readability**: Using well-named variables makes your code easier to understand.
3. **Flexibility**: You can easily change values in one place, affecting the entire program.

### Practice Exercise: Personal Library Catalog (20 minutes)

Now it's time to put your understanding of variables into practice! In this exercise, you'll create a simple program to catalog books in your personal library.

#### Task Description:
1. Create variables to store information about three books. For each book, you should have:
   - Title (String)
   - Author (String)
   - Publication Year (int)
   - Number of Pages (int)
   - Whether you've read it or not (boolean)
2. Assign values to these variables for three different books.
3. Use `System.out.println()` to display the information for each book in a formatted way.
4. Calculate and display some basic statistics:
   - The total number of pages across all books
   - The average publication year

## 4. Basic Java Operators

Operators are symbols that tell the compiler to perform specific mathematical or logical manipulations.

### 1. Arithmetic Operators
These are used to perform common mathematical operations:
- `+` (Addition): Adds two values
- `-` (Subtraction): Subtracts the right-hand operand from the left-hand operand
- `*` (Multiplication): Multiplies two values
- `/` (Division): Divides the left-hand operand by the right-hand operand
- `%` (Modulus): Returns the remainder of a division operation

### 2. Assignment Operator
- `=` : Assigns a value to a variable

### 3. Compound Assignment Operators
These perform an operation and assignment in one step:
- `+=` : Add and assign
- `-=` : Subtract and assign
- `*=` : Multiply and assign
- `/=` : Divide and assign

### 4. Comparison Operators
These are used to compare two values:
- `==` : Equal to
- `!=` : Not equal to
- `>` : Greater than
- `<` : Less than
- `>=` : Greater than or equal to
- `<=` : Less than or equal to

### 5. Logical Operators
These are used to determine the logic between variables or values:
- `&&` : Logical AND
- `||` : Logical OR
- `!` : Logical NOT

### Practice with Operators
Try to guess the output of these operations:
1. `int result = 10 + 5 * 2;`
2. `boolean isAdult = (18 >= 18);`
3. `int x = 10; x += 5; x *= 2;`

## 5. Control Flow

### If Statements
If statements are fundamental to programming as they allow your code to make decisions and execute different code blocks based on conditions.

#### Basic If Statement
```java
if (condition) {
    // code to be executed if the condition is true
}
```

Example:
```java
int temperature = 25;
if (temperature > 30) {
    System.out.println("It's a hot day!");
}
```

#### If-Else Statement
```java
if (condition) {
    // code to be executed if the condition is true
} else {
    // code to be executed if the condition is false
}
```

Example:
```java
int temperature = 25;
if (temperature > 30) {
    System.out.println("It's a hot day!");
} else {
    System.out.println("It's not too hot today.");
}
```

#### Else-If Statement
```java
if (condition1) {
    // code to be executed if condition1 is true
} else if (condition2) {
    // code to be executed if condition2 is true
} else {
    // code to be executed if all conditions are false
}
```

Example:
```java
int temperature = 25;
if (temperature > 30) {
    System.out.println("It's a hot day!");
} else if (temperature > 20) {
    System.out.println("It's a nice day.");
} else {
    System.out.println("It's a bit chilly.");
}
```

#### Nested If Statements
You can also place if statements inside other if statements. This is called nesting.

Example:
```java
boolean isWeekend = true;
boolean isRaining = false;

if (isWeekend) {
    if (isRaining) {
        System.out.println("Let's stay home and watch a movie.");
    } else {
        System.out.println("Let's go for a picnic!");
    }
} else {
    System.out.println("It's a work day.");
}
```

### Practice Exercise: Grade Calculator (15 minutes)

Let's create a program that assigns letter grades based on numerical scores.

#### Task Description:
1. Create a program that takes a numerical grade (0-100) and prints the corresponding letter grade.
2. Use the following grading scale:
   - 90-100: A
   - 80-89: B
   - 70-79: C
   - 60-69: D
   - Below 60: F
3. The program should also handle invalid grades (below 0 or above 100).

### Loops
Loops are fundamental programming constructs that allow you to repeat a block of code multiple times. They're essential for efficient programming and are particularly useful when working with collections of data.

#### Why Use Loops?
Loops help you:
- Automate repetitive tasks
- Process collections of data efficiently
- Implement algorithms that require repeated operations

#### Types of Loops in Java
1. **for Loop**: Used when you know in advance how many times you want to repeat a block of code.
   ```java
   for (initialization; condition; update) {
       // code to be repeated
   }
   ```

2. **while Loop**: Used when you want to repeat a block of code as long as a condition is true.
   ```java
   while (condition) {
       // code to be repeated
   }
   ```

3. **do-while Loop**: Similar to while loop, but guarantees that the code block is executed at least once.
   ```java
   do {
       // code to be repeated
   } while (condition);
   ```

#### Loop Control Statements
Java provides statements to control the flow of loops:
- `break`: Exits the loop immediately
- `continue`: Skips the rest of the current iteration and moves to the next one

### Practice Exercise: Multiplication Table Generator (20 minutes)

Let's create a program that generates a multiplication table to practice using loops.

#### Task Description:
1. Create a program that prints out a multiplication table for numbers 1 through 5.
2. Use nested loops to generate the table.
3. The output should look something like this:
   ```
   1  2  3  4  5
   2  4  6  8 10
   3  6  9 12 15
   4  8 12 16 20
   5 10 15 20 25
   ```

## 6. Arrays

### What is an Array?
An array is a container that holds a fixed number of values of a single type. Think of an array as a row of boxes, where each box can hold an item of a specific type (like integers, strings, etc.).

### Why Use Arrays?
Arrays allow you to store multiple items of the same type under a single variable name. This makes it easier to:
- Group related data together
- Perform operations on multiple values efficiently
- Organize and manage large sets of data

### Declaring and Initializing Arrays
In Java, you can declare and initialize an array in several ways:

1. Declare an array without initializing:
   ```java
   int[] numbers;  // Declares an array of integers
   ```

2. Declare and allocate memory for the array:
   ```java
   int[] numbers = new int[5];  // Creates an array that can hold 5 integers
   ```

3. Declare, allocate memory, and initialize the array:
   ```java
   int[] numbers = {1, 2, 3, 4, 5};  // Creates and initializes an array with 5 integers
   ```

### Accessing Array Elements
Array elements are accessed using their index. In Java, array indices start at 0.

```java
int[] numbers = {10, 20, 30, 40, 50};
System.out.println(numbers[0]);  // Outputs: 10
System.out.println(numbers[2]);  // Outputs: 30
```

### Modifying Array Elements
You can change the value of an array element by assigning a new value to a specific index:

```java
numbers[1] = 25;  // Changes the second element (index 1) to 25
```

### Array Length
You can find out how many elements an array has using the `length` property:

```java
int arraySize = numbers.length;  // arraySize will be 5
```

### Iterating Through Arrays
You can use loops to iterate through array elements:

1. Using a for loop:
   ```java
   for (int i = 0; i < numbers.length; i++) {
       System.out.println(numbers[i]);
   }
   ```

2. Using an enhanced for loop (for-each loop):
   ```java
   for (int number : numbers) {
       System.out.println(number);
   }
   ```

### Common Array Operations
1. Finding the sum of array elements:
   ```java
   int sum = 0;
   for (int number : numbers) {
       sum += number;
   }
   ```

2. Finding the largest element:
   ```java
   int max = numbers[0];
   for (int i = 1; i < numbers.length; i++) {
       if (numbers[i] > max) {
           max = numbers[i];
       }
   }
   ```

### Practice Exercise: Temperature Tracker (20 minutes)

In this exercise, you'll create a program that tracks daily temperatures for a week and performs some basic analysis.

#### Task Description:
1. Create an array to store 7 daily temperature readings (as integers).
2. Initialize the array with temperature values for a week.
3. Calculate and print the average temperature.
4. Find and print the highest and lowest temperatures of the week.
5. Count how many days were above average temperature.

## 7. Working with Strings
Strings are fundamental in Java for handling text. Java provides a rich set of methods to manipulate and analyze strings efficiently.

### Why Are String Methods Important?
String methods allow you to:
- Modify and transform text
- Extract information from strings
- Compare and search within strings
- Perform various text-processing tasks

### Common String Methods
Here are some of the most frequently used String methods in Java:

1. **length()**: Returns the length of the string.
   ```java
   String str = "Hello";
   int length = str.length();  // length is 5
   ```

2. **charAt(int index)**: Returns the character at the specified index.
   ```java
   char ch = str.charAt(1);  // ch is 'e'
   ```

3. **substring(int beginIndex, int endIndex)**: Extracts a portion of the string.
   ```java
   String sub = str.substring(1, 4);  // sub is "ell"
   ```

4. **toLowerCase() and toUpperCase()**: Converts all characters to lower or upper case.
   ```java
   String lower = str.toLowerCase();  // lower is "hello"
   String upper = str.toUpperCase();  // upper is "HELLO"
   ```

5. **trim()**: Removes leading and trailing whitespace.
   ```java
   String trimmed = "  Hello  ".trim();  // trimmed is "Hello"
   ```

6. **replace(char oldChar, char newChar)**: Replaces all occurrences of a character.
   ```java
   String replaced = str.replace('l', 'x');  // replaced is "Hexxo"
   ```

7. **startsWith(String prefix) and endsWith(String suffix)**: Checks if the string starts or ends with the given text.
   ```java
   boolean starts = str.startsWith("He");  // true
   boolean ends = str.endsWith("lo");      // true
   ```

8. **contains(CharSequence s)**: Checks if the string contains the specified sequence of characters.
   ```java
   boolean contains = str.contains("ell");  // true
   ```

9. **split(String regex)**: Splits the string around matches of the given regular expression.
   ```java
   String[] parts = "Hello,World".split(",");  // parts is ["Hello", "World"]
   ```

10. **equals(Object obj)**: Compares this string to another object.
    ```java
    boolean isEqual = str.equals("Hello");  // true
    ```

### Important Note on String Immutability
Strings in Java are immutable, which means once a String object is created, it cannot be changed. Methods like `replace()` or `toUpperCase()` don't modify the original string; instead, they return a new string with the requested changes.

Think of a String like a word carved in stone. You can't change the carving, but you can make a new stone with a modified version of the word.

### Practice Exercise: Name Analyzer (20 minutes)

Let's create a program that analyzes names using various String methods.

#### Task Description:

1. Create a program that takes a full name (first name and last name) as a single string.
2. The program should:
   - Print the length of the full name
   - Extract and print the first name
   - Extract and print the last name
   - Print the initials (first letter of first name + first letter of last name)
   - Check if the name contains the letter 'a' (case insensitive)
   - Print the name in all uppercase

#### Example Code Structure:

```java
public class NameAnalyzer {
    public static void main(String[] args) {
        String fullName = "John Doe";  // You can change this to test different names

        // Your code goes here
        // Use various String methods to analyze the name

        // Print the results of your analysis
    }
}
```

#### Bonus Challenges
1. Handle middle names (extract middle name or middle initial)
2. Reverse the full name
3. Count the number of vowels in the name

## Key Takeaways

Congratulations! You've completed the Java Programming Bootcamp. Here's what you've learned:

1. Basic programming concepts and Java syntax
2. Variables and data types
3. Operators and expressions
4. Control flow with if statements and loops
5. Working with arrays
6. String manipulation



Remember, programming is like learning a new language or a musical instrument - it takes practice! Don't be discouraged if you don't understand everything right away. Keep coding, experimenting, and building small projects to reinforce what you've learned.

## Glossary of Key Terms
- JDK: Java Development Kit
- IDE: Integrated Development Environment
- Variable: A container for storing data values
- Data Type: Specifies the type of data that a variable can hold
- Operator: A symbol that tells the compiler to perform specific mathematical or logical manipulations
- Control Flow: The order in which individual statements, instructions, or function calls are executed or evaluated
- Array: A container object that holds a fixed number of values of a single type
- String: A sequence of characters
- Loop: A programming construct that repeats a group of commands
- Conditional Statement: A feature of coding that performs different computations or actions depending on whether a programmer-specified condition evaluates to true or false
