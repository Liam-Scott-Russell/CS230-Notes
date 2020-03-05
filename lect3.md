# Lecture 3

## User Input

Is acquired by using the Scanner class, located in `java.util.*`
You create a scanner object, e.g `Scanner console = new Scanner(System.in);`
The scanner object will translate the user input into types that you can utilize in your program.

// table to use scanner

### Steps to read input from user

1. `import` the `Scanner` class
1. Construct a `Scanner` object
1. Display a prompt message
1. Define a variable to receive the value
1. Read input

> Use `println` for excercises in CodeRunner, not `print` to keep outputs tidy

## Expressions

An expression is code that can be evaluated to give a single value:

### Operator tables

//insert

> If you divide two integers, the output will be an integer. If you want a double as an output, make one of the operands a double.

When different operands are operated upon, Java will perform a widening conversion automatically.

### Increment Operators

- Post Increment (`i++`): increment the value of the variable after assigning
- Pre Increment (`++i`): Increment the value then assign value.

e.g  // add all the stufff

### Order of precedence

add tables

### Logical Expressions

- Operators
- order

When using && and || to evaluate an expression, if the outcome is able to be determined after looking at the first variable, the program will not look at the 2nd variable.
This will happen when the first variable evaluates True with an `or` statement, or when the first evaluates False with an `and` statement.
e.g

``` sh
    int a = 1;
    int b = 2;
    System.out.println(a>0 || b>a/0) 
    //will not error on 2nd expression as the first will evaluate True.
```

Notes:

- Mathematical shortcuts do not work

asd
