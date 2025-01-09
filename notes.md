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