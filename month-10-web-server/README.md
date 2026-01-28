# Month 10: Web Server

## 🎯 Learning Objectives

- Build HTTP servers
- Implement routing
- Handle requests and responses
- Work with middleware
- Template rendering
- RESTful API design

## 📋 Project Description

Develop a simple web server with REST endpoints using a web framework like Actix-web or Axum. Build a complete API with CRUD operations and learn web development in Rust.

## ✨ Features to Implement

1. **Basic Server**
   - HTTP server setup
   - Basic routing (GET, POST, PUT, DELETE)
   - JSON request/response handling
   - Error handling and status codes

2. **Advanced Features**
   - Middleware (logging, auth)
   - Template rendering
   - Static file serving
   - Database integration
   - Authentication/Authorization

## 🔧 Technical Concepts

- HTTP server implementation
- Routing and handlers
- Request/response lifecycle
- Middleware patterns
- State management
- Async handlers
- RESTful API design

## 🚀 Getting Started

```bash
cd month-10-web-server

# Add dependencies
cargo add actix-web
cargo add tokio --features full
cargo add serde --features derive
cargo add serde_json

# Build and run
cargo build
cargo run

# Test endpoints
curl http://localhost:8080/
curl -X POST http://localhost:8080/api/users -d '{"name":"John"}'
```

## 📝 Exercises

1. Set up basic HTTP server
2. Implement GET endpoint
3. Add POST endpoint with JSON
4. Create PUT and DELETE endpoints
5. Add middleware (logging)
6. Implement error handling
7. Add database integration

## 🎓 Key Takeaways

After completing this project, you should understand:
- Web server architecture
- HTTP request handling
- Routing patterns
- Middleware concepts
- API design principles
- Async web frameworks
- State management in web apps

## 📚 Resources

- [actix-web documentation](https://actix.rs/)
- [axum documentation](https://docs.rs/axum/)
- [tokio documentation](https://tokio.rs/)
- [REST API design guide](https://restfulapi.net/)
