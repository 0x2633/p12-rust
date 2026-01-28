# Getting Started with p12-rust

Welcome to the 12-month Rust learning journey! This guide will help you get started with the projects.

## Prerequisites

### Install Rust

1. Visit [rustup.rs](https://rustup.rs/) or run:
   ```bash
   curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
   ```

2. Verify installation:
   ```bash
   rustc --version
   cargo --version
   ```

3. Update Rust (recommended):
   ```bash
   rustup update
   ```

### Install Development Tools

```bash
# Install rust-analyzer (LSP server for IDE support)
rustup component add rust-analyzer

# Install rustfmt (code formatter)
rustup component add rustfmt

# Install clippy (linter)
rustup component add clippy
```

## Starting Your First Project

### Month 1: Hello CLI

1. Navigate to the first project:
   ```bash
   cd month-01-hello-cli
   ```

2. Initialize a new Rust project:
   ```bash
   cargo new hello-cli
   cd hello-cli
   ```

3. Open `src/main.rs` and start coding!

4. Build and run:
   ```bash
   cargo build    # Compile the project
   cargo run      # Compile and run
   cargo test     # Run tests
   cargo check    # Quick compile check
   ```

### Useful Cargo Commands

```bash
# Create new binary project
cargo new project-name

# Create new library project
cargo new --lib library-name

# Add dependencies
cargo add serde

# Update dependencies
cargo update

# Build release version (optimized)
cargo build --release

# Format code
cargo fmt

# Run linter
cargo clippy

# Generate documentation
cargo doc --open
```

## Project Workflow

1. **Read** the month's README for learning objectives
2. **Plan** your implementation approach
3. **Code** incrementally, testing as you go
4. **Test** your code with `cargo test`
5. **Refactor** and improve your solution
6. **Document** your code with comments and docs
7. **Move** to the next project when ready

## Learning Tips

- **Don't rush**: Take time to understand concepts
- **Read errors carefully**: Rust's compiler is very helpful
- **Experiment**: Modify code to see what happens
- **Use the docs**: `cargo doc --open` is your friend
- **Practice daily**: Even 30 minutes helps
- **Ask for help**: Rust community is friendly and helpful

## Recommended Resources

### Official Documentation
- [The Rust Programming Language Book](https://doc.rust-lang.org/book/)
- [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
- [Standard Library Docs](https://doc.rust-lang.org/std/)

### Practice
- [Rustlings](https://github.com/rust-lang/rustlings) - Small exercises
- [Exercism Rust Track](https://exercism.org/tracks/rust)
- [Rust Playground](https://play.rust-lang.org/) - Online REPL

### Community
- [Rust Users Forum](https://users.rust-lang.org/)
- [r/rust on Reddit](https://www.reddit.com/r/rust/)
- [Rust Discord](https://discord.gg/rust-lang)

## IDE Setup

### VS Code (Recommended)
1. Install [VS Code](https://code.visualstudio.com/)
2. Install extensions:
   - rust-analyzer
   - Even Better TOML
   - CodeLLDB (for debugging)

### Other IDEs
- **IntelliJ IDEA/CLion**: Install Rust plugin
- **Vim/Neovim**: Use coc-rust-analyzer or native LSP
- **Emacs**: Use rust-mode with lsp-mode

## Troubleshooting

### Common Issues

**Problem**: `cargo: command not found`  
**Solution**: Add `~/.cargo/bin` to your PATH

**Problem**: Slow compile times  
**Solution**: Use `cargo check` for faster feedback during development

**Problem**: Confusing error messages  
**Solution**: Read carefully - Rust errors usually suggest fixes!

**Problem**: Borrow checker errors  
**Solution**: This is normal! Read Chapter 4 of the Rust Book

## Next Steps

1. Complete the installation checklist
2. Start with Month 1: Hello CLI
3. Follow the learning path sequentially
4. Track your progress in the main README
5. Enjoy learning Rust!

Good luck on your Rust learning journey! 🦀
