# Month 5: Web Scraper

## 🎯 Learning Objectives

- Make HTTP requests
- Parse HTML content
- Work with async/await
- Handle network errors
- Process and extract data
- Understand lifetimes and references

## 📋 Project Description

Create a web scraper that extracts data from websites. Learn how to make HTTP requests, parse HTML, and handle asynchronous operations in Rust.

## ✨ Features to Implement

1. **Basic Scraper**
   - Fetch web pages
   - Parse HTML content
   - Extract specific elements
   - Save data to file

2. **Advanced Features**
   - Scrape multiple pages
   - Handle pagination
   - Rate limiting
   - Error recovery and retry logic
   - Export to CSV or JSON

## 🔧 Technical Concepts

- HTTP client operations
- Async/await syntax
- HTML parsing and DOM traversal
- CSS selectors
- Error handling in async context
- Working with futures
- Data extraction and transformation

## 🚀 Getting Started

```bash
cd month-05-web-scraper

# Add dependencies
cargo add reqwest --features blocking
cargo add scraper
cargo add tokio --features full

# Build and run
cargo build
cargo run -- https://example.com
```

## 📝 Exercises

1. Fetch a web page using reqwest
2. Parse HTML with scraper
3. Extract specific data using CSS selectors
4. Save extracted data to JSON
5. Implement async version
6. Add rate limiting
7. Handle errors gracefully

## 🎓 Key Takeaways

After completing this project, you should understand:
- Making HTTP requests in Rust
- Async programming basics
- HTML parsing techniques
- Error handling in async code
- Working with external APIs
- Data extraction patterns

## 📚 Resources

- [reqwest documentation](https://docs.rs/reqwest/)
- [scraper documentation](https://docs.rs/scraper/)
- [tokio documentation](https://tokio.rs/)
- [Async Book](https://rust-lang.github.io/async-book/)
