# Company-Employees-Management
# 👨‍💼 Employee Management System

A **Java-based Employee Management System** designed to manage employee records through a simple desktop graphical user interface.

The application allows users to add, view, update, and remove employee information using a Java Swing interface connected to a database.

## 📌 About the Project

The Employee Management System provides a centralized application for managing employee records.

### Main functionalities

- 🔐 User login
- 👤 Add new employees
- 🔍 View employee details
- ✏️ Update employee information
- 🗑️ Remove employees
- 🏠 Dashboard/home interface
- 🗄️ Database connectivity

## ✨ Features

### 🔐 Login System

- Secure login interface
- User authentication before accessing the system

### ➕ Add Employee

Allows users to add employee information such as:

- Employee ID
- Name
- Personal details
- Contact information
- Job-related information

### 👀 View Employee

Users can search for and view employee records stored in the database.

### ✏️ Update Employee

Existing employee information can be modified when required.

### 🗑️ Remove Employee

Employees can be removed from the system using their employee information.

### 🏠 Home Dashboard

Provides access to the different employee management operations from a central interface.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **Java** | Core programming language |
| **Java Swing** | Graphical User Interface |
| **AWT** | GUI components and event handling |
| **JDBC** | Database connectivity |
| **MySQL** | Data storage |
| **NetBeans** | Development environment |

## 📁 Project Structure

```text
Employee-Management-System/
│
├── src/
│   ├── employee/
│   │   └── management/
│   │       └── system/
│   │           ├── AddEmployee.java
│   │           ├── Conn.java
│   │           ├── Home.java
│   │           ├── Login.java
│   │           ├── RemoveEmployee.java
│   │           ├── Splash.java
│   │           ├── UpdateEmployee.java
│   │           └── ViewEmployee.java
│   │
│   └── icons/
│       ├── add_employee.jpg
│       ├── delete.png
│       ├── details.jpg
│       ├── front.jpg
│       ├── home.jpg
│       ├── print.jpg
│       ├── remove.jpg
│       ├── second.jpg
│       └── view.jpg
│
├── nbproject/
├── build.xml
├── manifest.mf
├── .gitignore
└── README.md
```

## ⚙️ Requirements

Before running the project, install:

- **Java JDK**
- **NetBeans IDE** (recommended)
- **MySQL Server**
- **MySQL Connector/J**
- Required Java libraries

Check your Java installation:

```bash
java -version
```

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/employee-management-system.git
```

Replace `your-username` with your GitHub username.

### 2. Open the Project

Open **NetBeans IDE** and select:

```text
File → Open Project
```

Choose the `Employee-Management-System` project folder.

### 3. Configure the Database

The application uses a database connection through:

```text
src/employee/management/system/Conn.java
```

Open `Conn.java` and configure the MySQL connection according to your local setup.

You will need to create the required database and employee table before running the application.

### 4. Add Required Dependencies

Make sure the **MySQL JDBC driver** is available in the project libraries.

### 5. Run the Application

Run:

```text
Splash.java
```

The application will start with the splash screen and then open the login interface.

## 🔄 Application Workflow

```text
             Login
               │
               ▼
          Home Dashboard
               │
       ┌───────┼────────┐
       │       │        │
       ▼       ▼        ▼
     Add     View     Update
 Employee   Employee  Employee
       │       │        │
       └───────┼────────┘
               │
               ▼
          Remove Employee
```

## 🗄️ Database

The application uses **MySQL** for storing employee information.

Java communicates with the database using **JDBC (Java Database Connectivity)**.

The `Conn.java` class is responsible for establishing the database connection.

## 📚 Learning Objectives

This project provides practical experience with:

- Java programming
- Object-Oriented Programming
- Java Swing
- GUI development
- Event handling
- JDBC
- MySQL
- CRUD operations
- Database connectivity
- Form handling
- Exception handling

## 🔮 Future Improvements

The system can be enhanced with:

- 📊 Admin dashboard with employee statistics
- 🔑 Role-based access control
- 🔍 Advanced employee search and filtering
- 📸 Employee profile photographs
- 📄 PDF employee reports
- 📧 Email notifications
- 📱 Web/mobile version
- 📊 Employee attendance management
- 💰 Salary and payroll management
- 🏖️ Leave management
- 🔒 Improved password security
- ☁️ Cloud database support

## 🤝 Contribution

Contributions and improvements are welcome.

To contribute:

```bash
git clone https://github.com/your-username/employee-management-system.git
```

Create a new branch:

```bash
git checkout -b feature/new-feature
```

Make your changes, commit them, and create a pull request.

## 📜 License

If this project is based on or adapted from an existing project, retain the original license and required attribution.

If you are the original author, add an appropriate open-source license to the repository.

## 👩‍💻 Author

**Sonal  Agrawal**

B.Tech Computer Science Engineering (AI)

---

⭐ If you find this project useful, consider giving the repository a star!
