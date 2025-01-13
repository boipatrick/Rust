## Intro
Cargo is the Rust’s build system and package manager.

Cargo new- creates a new project

Cargo build - builds a project

Cargo run - builds and runs a project in one step


Cargo check - builds a project without producing a binary to check for errors




##  Variables and Mutability
    In rust variables are immuttable and this comes in handy when you write code in a way that takes advantage of the safety and easy concurrency that Rust offers.

    You can also decide otherwise and this is where now you use mut.


## Constants
- Values here are not allowed to change
- You cannot use the mut with constants
- The Const keyword is used here and the type of the value must be annotated
- Can be declared in any scope
- Naming convenction use UPPERCASE with underscores between the words.

## Shadowing

+ Shadowing allows you to declare a new variable with the same name as an existing variable. The new variable "shadows" the previous one.

+ We use let to redeclare the variable

+ Its purpose is to transform the value while keeping the variable name

+ The shadowed variable is only accessible until it's redeclared. Shadowing ends when the scope ends.

+ Makes code cleaner by reducing the need for additional variable names.

+ Enables safe transformations without accidentally modifying the original variable.

##  Data Types
+ Every value in Rust is of a certain data type, which tells Rust what kind of
data is being specified so it knows how to work with that data.

+ I'll cover Scalar and Compound types

+ Rust is a statically typed language meaning it must know all data types of variables at compile time.

### Scalar
Represents a single value.
Rust has 4 types
+ Integers
+ Boolean
+ floating- point numbers
+ Characters

### Compound
Tuple
+ A tuple is a general way of grouping together a number of values with a variety of types into one compound type. 
+ Tuples have a fixed length: once declared, they cannot grow or shrink in size.


### Array
Another method of storing values
Has a fixed length
The values must be of the same data type.
We use square brackets []

## Functions
- Prevalent in rust

- main function is the entry point of most programs

- fn allows us to create a function

- rust code uses snake case- in which all letters are lowercase and underscores separate
words.

### Statements and Expressions

## Functions With return Values
+ Functions can return values to the code that calls them

## Comments
- In Rust, the idiomatic comment style starts a comment with two slashes,
and the comment continues until the end of the line.

// Comment goes here.

## Control Flow

+ The ability to run some code depending on whether a condition is true and to run some code repeatedly while a condition is true are basic building
blocks in most programming languages.
+ The most common constructs that let you control the flow of execution of Rust code are if expressions and loops.

### If Expressions

- “If this condition is met, run this block of code. If the condition is not met, do not run this block of code.”
- Unlike other languages such as Ruby and JavaScript, Rust will not automatically try to
convert non-Boolean types to a Boolean. You must be explicit and always
provide if with a Boolean as its condition.

### Handling multiple conditions with else if
- You can use multiple conditions by combining if and else in an else if
expression.

- Using too many else if expressions can clutter your code, so if you have
more than one, you might want to refactor your code.

- A powerful Rust branching construct called match is used for these cases.


## Repition with Loops
- Rust has three types loop, while and for.

+ The loop keyword tells Rust to execute a block of code over and over again
forever or until you explicitly tell it to stop.

fn main() {
    loop {
println!("again!");
}
}

## Rust successfully Installed

### Conditional Loops with while

Stack
Heap - disorganized

+ Pushing to the stack is faster than allocating on the heap because the allocator never
has to search for a place to store new data; that location is always at the top of the stack.

### Ownership Rules
Each value in Rust has an owner.
There can only be one owner at a time.
When the owner goes out of scope, the value will be dropped.

## Variable scope

The String Type

## Memory and Allocation

+ 

## Understanding Ownership in Rust"