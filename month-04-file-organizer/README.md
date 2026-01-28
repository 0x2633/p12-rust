# Month 4: File Organizer

## 🎯 Learning Objectives

- Master file system operations
- Work with paths and directories
- Pattern matching and filtering
- Error handling for I/O operations
- String processing and regex
- Understand module organization

## 📋 Project Description

Develop a utility that automatically organizes files in a directory by type, date, or custom rules. This tool helps manage cluttered directories by sorting files into appropriate folders.

## ✨ Features to Implement

1. **Basic Organizer**
   - Scan directory for files
   - Categorize by file extension
   - Move files to type-specific folders
   - Handle duplicate filenames

2. **Advanced Features**
   - Organize by date (created/modified)
   - Custom organization rules
   - Recursive directory processing
   - Undo functionality
   - Dry-run mode (preview changes)

## 🔧 Technical Concepts

- File system traversal with `std::fs`
- Path manipulation with `std::path`
- File metadata and attributes
- Moving and copying files
- Error handling for I/O operations
- Regular expressions
- Iterator patterns

## 🚀 Getting Started

```bash
cd month-04-file-organizer

# Add dependencies
cargo add walkdir
cargo add regex
cargo add chrono

# Build and run
cargo build
cargo run -- organize /path/to/directory
cargo run -- --dry-run /path/to/directory
```

## 📝 Exercises

1. List all files in a directory
2. Categorize files by extension
3. Create folders for each file type
4. Move files to appropriate folders
5. Handle duplicate filenames
6. Add date-based organization
7. Implement dry-run mode

## 🎓 Key Takeaways

After completing this project, you should understand:
- File system operations in Rust
- Path manipulation and validation
- Working with file metadata
- Error handling for I/O
- Iterator patterns and transformations
- Organizing code into modules

## 📚 Resources

- [std::fs module](https://doc.rust-lang.org/std/fs/)
- [std::path module](https://doc.rust-lang.org/std/path/)
- [walkdir crate](https://docs.rs/walkdir/)
- [regex crate](https://docs.rs/regex/)
