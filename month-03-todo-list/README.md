# Month 3: Todo List CLI

## 🎯 Learning Objectives

- Work with collections (Vec, HashMap)
- Define and use structs
- Implement file I/O operations
- Serialize/deserialize with JSON
- Build a complete CLI application
- Understand ownership and borrowing

## 📋 Project Description

Build a command-line todo list application that allows users to add, view, complete, and delete tasks. Tasks are persisted to a file so they survive program restarts.

## ✨ Features to Implement

1. **Core Features**
   - Add new tasks
   - List all tasks
   - Mark tasks as complete
   - Delete tasks
   - Save/load from file

2. **Advanced Features**
   - Task priorities (high, medium, low)
   - Due dates
   - Task categories/tags
   - Search and filter tasks
   - Edit existing tasks

## 🔧 Technical Concepts

- Vectors and dynamic arrays
- Structs and methods
- File I/O with `std::fs`
- JSON serialization with `serde`
- Command-line argument parsing
- Error propagation with `?` operator
- Ownership and borrowing in practice

## 🚀 Getting Started

```bash
cd month-03-todo-list

# Add dependencies
cargo add serde --features derive
cargo add serde_json
cargo add clap --features derive

# Build and run
cargo build
cargo run -- add "Learn Rust"
cargo run -- list
cargo run -- complete 1
```

## 📝 Exercises

1. Create a Task struct with id, description, completed status
2. Implement add, list, complete, and delete commands
3. Add file persistence using JSON
4. Implement priority levels
5. Add due date functionality
6. Create search/filter capabilities

## 🎓 Key Takeaways

After completing this project, you should understand:
- How to structure data with structs
- Working with collections effectively
- File I/O patterns in Rust
- Serialization and deserialization
- Building user-friendly CLI applications
- Proper error handling patterns

## 📚 Resources

- [The Rust Book - Chapter 8: Collections](https://doc.rust-lang.org/book/ch08-00-common-collections.html)
- [serde documentation](https://serde.rs/)
- [clap documentation](https://docs.rs/clap/)
- [std::fs module](https://doc.rust-lang.org/std/fs/)
