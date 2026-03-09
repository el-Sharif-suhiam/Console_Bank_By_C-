## C++ Console Banking Project with OOP

This project implements a fully object-oriented banking system in C++ using core OOP principles:

**Key OOP Features**
- **Encapsulation**: Data members (account number, balance, credentials) are protected within classes with controlled access via methods
- **Inheritance**: Admin and customer roles likely inherit from a base User class with shared authentication
- **Abstraction**: Complex operations (transactions, file handling) are hidden behind simple method calls
- **Polymorphism**: Different account types may share common interfaces with specialized behavior

**Architecture**
- **User Classes**: Separate classes for Customer and Admin with role-specific privileges
- **Account Management**: Objects represent individual accounts with deposit, withdraw, and transfer methods
- **File Persistence**: Text files store account data between sessions using structured I/O operations
- **Security**: Login system validates username (User1) and password (1234) before access

**Technical Implementation**
- **Console Interface**: Menu-driven navigation using C++ iostream
- **Data Structures**: Arrays or vectors manage multiple account objects
- **Error Handling**: Input validation prevents invalid transactions
- **Compilation**: Built and run through Bank Project.sln in Visual Studio
