# Line by Line Breakdown: Java Syntax Basics

### Line 1: `public class Main {`
* `public`: An access modifier meaning this class is visible to the entire program.
* `class`: The keyword used to define a container for Java code.
* `Main`: The identifier for this class. Must match the file name `Main.java` exactly.
* `{`: Opening curly brace defining the start of the class body.

### Line 2: `public static void main(String[] args) {`
* `public`: Allows the JVM to invoke this method from outside the class.
* `static`: Means the method belongs to the class itself, so the JVM can run it without creating an object instance first.
* `void`: Indicates that this method does not return any value back after execution completes.
* `main`: The required method name that serves as the execution entry point.
* `String[] args`: An array parameter that captures command line arguments passed into the program.
* `{`: Opening curly brace defining the start of the `main` method execution block.

### Line 3: `System.out.println("Hello World");`
* `System`: A built-in standard system class in Java.
* `out`: The output stream object connected to the console/terminal.
* `println`: The method that outputs text to the screen followed by a newline character.
* `"Hello World"`: A string literal enclosed in double quotes.
* `;`: Required terminator at the end of every Java statement.

### Line 4: `}`
* Closes the `main` method execution block.

### Line 5: `}`
* Closes the `Main` class definition.