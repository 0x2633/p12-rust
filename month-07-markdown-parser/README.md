# Month 7: Markdown Parser

## 🎯 Learning Objectives

- String parsing and manipulation
- Recursive algorithms
- Enums and pattern matching
- State machines
- Building domain-specific parsers
- Advanced string processing

## 📋 Project Description

Implement a basic Markdown to HTML converter. Parse Markdown syntax and generate corresponding HTML output. This project teaches text processing and parser implementation.

## ✨ Features to Implement

1. **Basic Parser**
   - Headers (# to ######)
   - Bold and italic text
   - Links and images
   - Paragraphs
   - Lists (ordered and unordered)

2. **Advanced Features**
   - Code blocks and inline code
   - Blockquotes
   - Tables
   - Horizontal rules
   - Nested structures

## 🔧 Technical Concepts

- String slicing and iteration
- Enums for token representation
- Pattern matching
- Recursive parsing
- State management
- Regular expressions
- String builders and formatting

## 🚀 Getting Started

```bash
cd month-07-markdown-parser

# Add dependencies
cargo add regex

# Build and run
cargo build
cargo run -- input.md output.html
echo "# Hello World" | cargo run
```

## 📝 Exercises

1. Parse basic headers
2. Handle bold and italic formatting
3. Parse links and images
4. Implement list parsing
5. Add code block support
6. Handle nested structures
7. Generate HTML output

## 🎓 Key Takeaways

After completing this project, you should understand:
- String parsing techniques
- Building parsers from scratch
- Pattern matching in depth
- Recursive algorithms
- State management
- Text processing best practices

## 📚 Resources

- [Markdown Guide](https://www.markdownguide.org/)
- [CommonMark Spec](https://spec.commonmark.org/)
- [regex crate](https://docs.rs/regex/)
- [String methods](https://doc.rust-lang.org/std/string/struct.String.html)
