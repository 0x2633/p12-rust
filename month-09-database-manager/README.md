# Month 9: Database Manager

## 🎯 Learning Objectives

- SQL database integration
- CRUD operations (Create, Read, Update, Delete)
- Connection pooling
- Query building
- Database migrations
- ORM patterns

## 📋 Project Description

Build a CLI database management tool that performs CRUD operations on a SQLite database. Learn how to integrate databases into Rust applications and manage data persistence.

## ✨ Features to Implement

1. **Basic Operations**
   - Create tables
   - Insert records
   - Query records
   - Update records
   - Delete records

2. **Advanced Features**
   - Database migrations
   - Connection pooling
   - Complex queries (JOIN, GROUP BY)
   - Transaction support
   - Data export/import

## 🔧 Technical Concepts

- SQL database operations
- SQLite integration
- Query builders
- Connection management
- Prepared statements
- Error handling for database operations
- Async database operations

## 🚀 Getting Started

```bash
cd month-09-database-manager

# Add dependencies
cargo add rusqlite
cargo add sqlx --features sqlite,runtime-tokio-native-tls

# Build and run
cargo build
cargo run -- create-table users
cargo run -- insert user "John Doe" "john@example.com"
cargo run -- list users
```

## 📝 Exercises

1. Connect to SQLite database
2. Create tables programmatically
3. Implement INSERT operations
4. Implement SELECT queries
5. Add UPDATE functionality
6. Add DELETE functionality
7. Implement transactions

## 🎓 Key Takeaways

After completing this project, you should understand:
- Database integration in Rust
- SQL operations from code
- Connection management
- Error handling for databases
- Data persistence patterns
- Query optimization basics

## 📚 Resources

- [rusqlite documentation](https://docs.rs/rusqlite/)
- [sqlx documentation](https://docs.rs/sqlx/)
- [SQLite documentation](https://www.sqlite.org/docs.html)
- [Database best practices](https://use-the-index-luke.com/)
