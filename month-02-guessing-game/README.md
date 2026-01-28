# Month 2: Guessing Game

## 🎯 Learning Objectives

- Work with random number generation
- Implement loops and control flow
- Master pattern matching with `match`
- Handle user input and errors gracefully
- Understand comparison and ordering
- Use external crates (dependencies)

## 📋 Project Description

Create an interactive number guessing game where the computer generates a random number and the player tries to guess it. The program provides feedback on whether each guess is too high or too low.

## ✨ Features to Implement

1. **Basic Game**
   - Generate a random number between 1 and 100
   - Accept player guesses
   - Provide "too high" or "too low" feedback
   - Congratulate on correct guess

2. **Enhanced Version**
   - Track number of attempts
   - Implement difficulty levels (different ranges)
   - Add option to play again
   - Keep high score (fewest attempts)

## 🔧 Technical Concepts

- Using external crates (`rand`)
- Loops: `loop`, `while`, `for`
- Pattern matching with `match`
- `Result` and error handling
- Comparison operations and `Ordering`
- Type conversion and parsing
- Breaking out of loops

## 🚀 Getting Started

```bash
# Navigate to project directory
cd month-02-guessing-game

# Add rand dependency
cargo add rand

# Or manually edit Cargo.toml:
# [dependencies]
# rand = "0.8"

# Build and run
cargo build
cargo run
```

## 📝 Exercises

1. Implement the basic guessing game
2. Add attempt counter
3. Create multiple difficulty levels
4. Add input validation for non-numeric input
5. Implement a "play again" feature
6. Create a scoring system

## 🎓 Key Takeaways

After completing this project, you should understand:
- How to use external crates in Rust
- Loop patterns and when to use each
- Pattern matching for control flow
- Error handling with Result<T, E>
- Random number generation
- User interaction patterns

## 📚 Resources

- [The Rust Book - Chapter 2: Guessing Game](https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html)
- [rand crate documentation](https://docs.rs/rand/)
- [std::cmp::Ordering](https://doc.rust-lang.org/std/cmp/enum.Ordering.html)
