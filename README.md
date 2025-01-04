# Simple-Rust-Guessing-Game

This Project is from Rust Book and is used by me to learn Rust.

## Learning One

1. To take input from the command line we use the `std::io` library
   Command : `use std::io;`
2. The io library comes from the standard library, known as `std:`
3. If a type you want to use isn’t in the prelude, you have to bring that type into scope explicitly with a `use` statement.
4. Using the std::io library provides you with a number of useful features, including the ability to accept user input.
5. `String` is a string type provided by the standard library that is a growable, UTF-8 encoded bit of text.

## Learning Two

1. The `::` syntax in the `::new` line indicates that **new is an associated function of the String type**. An associated function is a function that’s implemented on a type, in this case String. This new function creates a new, empty string. You’ll find a new function on many types because it’s a common name for a function that makes a new value of some kind.
2. In full, the `let mut guess = String::new();` line has created a mutable variable that is currently bound to a new, empty instance of a String.

## Learning Three

1. Call the stdin function from the io module, which will allow us to handle user input:

### **NOTE**

`    If we hadn’t imported the io library with use std::io; at the beginning of the program, we could still use the function by writing this function call as std::io::stdin. The stdin function returns an instance of std::io::Stdin, which is a type that represents a handle to the standard input for your terminal.`
