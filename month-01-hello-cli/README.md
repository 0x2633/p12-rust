# Month 1: Hello CLI - Command Line Interface Basics

## 🎯 Learning Objectives

- Master basic Rust syntax and structure
- Understand variables, data types, and mutability
- Work with functions and parameters
- Handle user input and output
- String manipulation and formatting
- Introduction to error handling

## 📋 Project Description

Build a simple command-line calculator or greeting program that demonstrates fundamental Rust concepts. This project serves as your introduction to Rust programming.

## ✨ Features to Implement

1. **Basic Calculator**
   - Perform addition, subtraction, multiplication, and division
   - Read numbers from command-line arguments or user input
   - Display results in a formatted manner

2. **Interactive Greeting Program**
   - Prompt user for their name
   - Display a personalized greeting
   - Ask for age and calculate birth year

## 🔧 Technical Concepts

- `println!` and `print!` macros
- Variables and mutability (`let` and `let mut`)
- Data types: integers, floats, strings
- Functions and return values
- Reading user input with `std::io`
- String operations and formatting
- Basic error handling

## 🚀 Getting Started

```bash
# Create new Rust project
cargo new month-01-hello-cli
cd month-01-hello-cli

# Build the project
cargo build

# Run the project
cargo run

# Run with arguments
cargo run -- arg1 arg2
```

## 📝 Exercises

1. Create a calculator that accepts two numbers and an operator
2. Add input validation to ensure valid numbers
3. Create a temperature converter (Celsius to Fahrenheit)
4. Build a simple unit converter (miles to kilometers, etc.)

## 🎓 Key Takeaways

After completing this project, you should understand:
- How to create and structure a Rust project
- Basic Rust syntax and conventions
- How to compile and run Rust programs
- Working with standard input/output
- Basic error handling patterns

## 📚 Resources

- [The Rust Book - Chapter 2: Guessing Game](https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html)
- [Rust by Example - Hello World](https://doc.rust-lang.org/rust-by-example/hello.html)
- [std::io module](https://doc.rust-lang.org/std/io/)
