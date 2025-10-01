# Month 6: REST API Client

## 🎯 Learning Objectives

- Work with RESTful APIs
- JSON parsing and serialization
- Handle HTTP methods (GET, POST, PUT, DELETE)
- Authentication and headers
- Error handling for network operations
- Build practical API integrations

## 📋 Project Description

Build a CLI tool that interacts with a public REST API (e.g., GitHub API, weather API, or currency exchange API). Practice making authenticated requests and handling API responses.

## ✨ Features to Implement

1. **Basic Client**
   - GET requests to fetch data
   - Parse JSON responses
   - Display formatted output
   - Handle API errors

2. **Advanced Features**
   - POST/PUT/DELETE operations
   - Authentication (API keys, tokens)
   - Rate limiting and retry logic
   - Caching responses
   - Multiple API endpoints

## 🔧 Technical Concepts

- HTTP client with reqwest
- JSON serialization/deserialization
- Environment variables for secrets
- Builder pattern
- Custom error types
- Async/await in practice
- Testing with mock APIs

## 🚀 Getting Started

```bash
cd month-06-rest-api-client

# Add dependencies
cargo add reqwest --features json
cargo add serde --features derive
cargo add serde_json
cargo add tokio --features full

# Build and run
cargo build
cargo run -- fetch-user octocat
```

## 📝 Exercises

1. Connect to a public API
2. Fetch and display data
3. Parse JSON responses into structs
4. Implement error handling
5. Add authentication support
6. Create POST/PUT endpoints
7. Implement caching

## 🎓 Key Takeaways

After completing this project, you should understand:
- RESTful API interactions
- JSON data handling
- Async HTTP operations
- Authentication patterns
- Error propagation and handling
- Environment configuration

## 📚 Resources

- [reqwest documentation](https://docs.rs/reqwest/)
- [GitHub API v3](https://docs.github.com/en/rest)
- [serde_json documentation](https://docs.rs/serde_json/)
- [REST API best practices](https://restfulapi.net/)
