# java-interpreter
Lox language is a interpreter written in Java. It includes a lexer, recursive descent parser, resolver and interpreter (evaluator) that can execute Lox programs. It supports variables, functions, classes, inheritance, closures, and control flow. This project follows the principles outlined from the "Crafting Interpreters" book by Robert Nystrom.  

## Prerequisites
* Java Development Kit (JDK) 8 or higher
* `javac` and `java` available in your PATH

## Install & Run
```
git clone https://github.com/ry-cha/java-interpreter.git
cd java-interpreter
javac com/craftinginterpreters/lox/*.java
```

Run a Lox script file:
```
java com.craftinginterpreters.lox.Lox example.lox
```
