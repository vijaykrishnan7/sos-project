# sos-learning Management System
# 🎓 Learning Management System – School of Skills

A simple and interactive **Learning Management System (LMS)** developed using **Python, Object-Oriented Programming (OOP), and Streamlit**.

This project was created as a collaborative learning project to understand how Python OOP concepts can be used to build a practical management system with a user-friendly web interface.

## 👥 Team Members

This project was developed collaboratively by:

- **Vijay Krishnan K**
- **Shakkira**
- **Ajas**
- **Shanul**

## 📌 Project Overview

The **School of Skills Learning Management System** is designed to manage basic academic and organizational activities of a skill-based educational institution.

The system provides separate management features for:

- 🎓 Students
- 📚 Courses
- 👨‍💼 Employees
- 📊 Student & staff activities
- 💰 Fee status
- 🎯 Student placement status
- 📝 Leave management
- 🏫 School information

The application uses Python classes and methods for the core management logic and **Streamlit** to provide an interactive web-based interface. 

## 🚀 Features

### 🏠 Dashboard

The dashboard provides an overview of the institution, including:

- Total number of courses
- Total employees
- Total students
- Number of placed students
- School information



### 📚 Course Management

The course module allows users to:

- View all available courses
- Search courses by name
- Search courses by category
- View course details
- Display course fee, duration, mode and instructor

The project currently includes courses such as **Data Science, Fashion Design, and Human Resource Management**.

### 👨‍💼 Employee Management

The employee module provides:

- Employee details
- Department information
- Salary information
- Phone number
- Employee status
- Leave management
- Updating employee phone number
- Updating employee salary
- Adding new employees



### 🎓 Student Management

The student module provides:

- Student information
- Course information
- Student status
- Fee payment status
- Admission type
- Placement status
- Leave management
- Adding new students
- Filtering students by status

 

### 📊 Activities & Statistics

The activities module provides statistics such as:

- Total students
- Passed students
- Dropped students
- Fee-paid students
- Students with pending fees
- New admissions
- Placed students



## 🧠 OOP Concepts Used

This project was mainly developed to practice **Object-Oriented Programming in Python**.

### Classes

The project contains several classes:

```text
SOS
│
├── Courses
├── Employees
└── Student

SOSActivities
```

The `Courses`, `Employees`, and `Student` classes inherit from the `SOS` class.

### Inheritance

Example:

```python
class Courses(SOS):
```

```python
class Employees(SOS):
```

```python
class Student(SOS):
```

This demonstrates inheritance by deriving specialized classes from the main `SOS` class. 

### Encapsulation

Private attributes are used for managing sensitive internal data such as employee and student leave:

```python
self.__leave = 0
```

Getter and update methods are then used to access or modify the value.

### Class Methods

Class methods are used for operations such as:

- Adding employees
- Adding students
- Searching courses
- Displaying courses
- Managing departments

For example:

```python
@classmethod
def search_course(cls, course_name):
```



## 🛠️ Technologies Used

- **Python**
- **Object-Oriented Programming (OOP)**
- **Streamlit**
- **HTML/CSS** through Streamlit customization
- **Git & GitHub**

The Streamlit application also uses custom CSS to create cards and improve the visual presentation of the dashboard.

## 📂 Project Structure

```text
Learning-Management-System/
│
├── pro.py
├── stream.py
└── README.md
```

### `pro.py`

Contains the main Python classes and management logic:

- `SOS`
- `Courses`
- `Employees`
- `Student`
- `SOSActivities`

It also contains sample course, employee and student data.

### `stream.py`

Contains the Streamlit interface and connects the OOP classes with the web application.

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/learning-management-system.git
```

### 2. Navigate to the project directory

```bash
cd learning-management-system
```

### 3. Install Streamlit

```bash
pip install streamlit
```

### 4. Run the application

```bash
streamlit run stream.py
```

The application will open in your browser.

## 🖥️ Application Navigation

The application contains the following sections:

```text
🏠 Dashboard
📚 Courses
👨‍💼 Employees
➕ Add Employees
🎓 Students
➕ Add Students
📊 Activities
ℹ️ SOS Details
```



## 🎯 Learning Objectives

Through this project, we practiced:

- Python OOP concepts
- Classes and objects
- Inheritance
- Encapsulation
- Instance methods
- Class methods
- Lists and data management
- Conditional statements
- Filtering and searching
- Streamlit application development
- Building an interactive dashboard
- Collaborative GitHub project development

## 🔮 Future Improvements

Some possible improvements for future versions include:

- 🔐 User authentication and login
- 🗄️ Database integration using MySQL/PostgreSQL
- 📱 Improved responsive UI
- 📈 More detailed analytics and charts
- 📄 Student report generation
- 📧 Email notifications
- 👤 Separate admin, staff and student accounts
- 🔄 Persistent data storage
- 📚 Assignment and attendance management

## 🙏 Acknowledgement

This project was developed as a **team learning project** with the support and collaboration of **Shakkira, Ajas, and Shanul**.

The project helped us gain practical experience in Python OOP, application development, and collaborative project work.

---

⭐ **If you find this project useful, consider giving the repository a star!**

### Made with Python 🐍 & Streamlit 🎈
