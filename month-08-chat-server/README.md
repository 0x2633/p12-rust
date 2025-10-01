# Month 8: Chat Server

## 🎯 Learning Objectives

- TCP networking fundamentals
- Multi-threading and concurrency
- Message passing with channels
- Synchronization primitives
- Client-server architecture
- Broadcasting messages

## 📋 Project Description

Create a multi-client chat server where multiple users can connect and send messages to each other. Learn concurrent programming and network communication in Rust.

## ✨ Features to Implement

1. **Basic Server**
   - Accept TCP connections
   - Receive messages from clients
   - Broadcast to all connected clients
   - Handle client disconnections

2. **Advanced Features**
   - Private messages
   - Chat rooms/channels
   - User authentication
   - Message history
   - Command system (/help, /users, etc.)

## 🔧 Technical Concepts

- TCP sockets with `std::net`
- Threading with `std::thread`
- Message passing with channels
- Shared state with Arc and Mutex
- Error handling in concurrent code
- Protocol design
- Client implementation

## 🚀 Getting Started

```bash
cd month-08-chat-server

# Build and run server
cargo build
cargo run -- server

# In another terminal, run client
cargo run -- client localhost:8080
```

## 📝 Exercises

1. Create basic TCP server
2. Accept multiple client connections
3. Implement message broadcasting
4. Add threading for concurrent clients
5. Use channels for message passing
6. Handle client disconnections
7. Build a simple client

## 🎓 Key Takeaways

After completing this project, you should understand:
- Network programming in Rust
- Concurrent programming patterns
- Thread safety and synchronization
- Message passing vs shared state
- Building client-server applications
- Protocol design basics

## 📚 Resources

- [std::net module](https://doc.rust-lang.org/std/net/)
- [std::thread module](https://doc.rust-lang.org/std/thread/)
- [std::sync module](https://doc.rust-lang.org/std/sync/)
- [The Rust Book - Chapter 20: Building a Multithreaded Web Server](https://doc.rust-lang.org/book/ch20-00-final-project-a-web-server.html)
