# 📚 Student Notes Management System

A web-based application developed using **Python Flask** that helps students securely create, upload, organize, and manage their academic notes and study materials in one place.

The application provides personalized user accounts, secure authentication, file management, and an easy-to-use interface to make managing study resources simple and efficient.

## 🌐 Live Demo

**Deployed Application:** https://deepikasnsapp.codegnan.app/

## ✨ Key Features

### 🔐 1. User Authentication & Security
- New user registration and login functionality.
- Secure password storage using password hashing.
- Authentication-based access to user accounts.
- Personalized welcome message displaying the logged-in user's name.

### 👤 2. User Profile Management
- Personalized user profile.
- View user-related information.
- Individual user experience.

### 📝 3. Notes Management
- Create and upload academic notes.
- Upload files and study materials.
- View uploaded notes and files.
- Edit existing notes.
- Delete unwanted notes.
- Manage personal study materials efficiently.

### 🔍 4. Filtering Functionality
- Filter notes to find relevant study materials.
- Easily organize and access uploaded notes.

### 🗄️ 5. Database Management
- MySQL database integration.
- Store and retrieve user information.
- Manage notes and associated records.
- Maintain user-specific data.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Flask | Web application framework |
| MySQL | Database management |
| HTML5 | Web page structure |
| CSS3 | Styling |
| Bootstrap | Responsive user interface |
| Jinja2 | Dynamic HTML templating |
| REST API Concepts | Client-server communication and backend operations |

## ⚙️ Technical Concepts Implemented

- **CRUD Operations:** Create, Read, Update, and Delete notes.
- **Authentication:** User registration and login.
- **Password Hashing:** Securely store passwords in hashed form instead of plain text.
- **Database Connectivity:** Connect Flask with MySQL.
- **File Handling:** Upload and manage study materials.
- **Dynamic Rendering:** Display personalized information using Jinja2 templates.
- **Routing:** Handle different application pages and requests using Flask routes.
- **REST API Concepts:** Understand and implement backend communication.

## 🚀 Installation & Setup

Follow these steps to run the project locally.

### Prerequisites

Make sure you have installed:

- Python 3.x
- MySQL Server
- MySQL Workbench (optional, for database management)
- VS Code or any code editor
- Git

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Navigate to the project directory:

```bash
cd Student-Notes-Management-System
```

### Step 2: Create a Virtual Environment

```bash
python -m venv venv
```

Activate the virtual environment.

**Windows:**
```bash
venv\Scripts\activate
```

**Mac/Linux:**
```bash
source venv/bin/activate
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Configure the Database

1. Start your MySQL server.
2. Create a database for the application.
3. Configure your database connection details in the project configuration.
4. Ensure the required database tables are created.

### Step 5: Run the Application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000/
```

## 📸 Application Preview

Add your application screenshots here to showcase the user interface.

Suggested screenshots:

1. Registration Page
2. Login Page
3. Personalized Dashboard
4. Notes Management Page
5. File Upload Functionality
6. User Profile Page

## 🎯 Project Objective

The main objective of this project is to provide students with a simple, secure, and personalized platform to manage their academic notes and study materials while gaining practical experience in Python Flask, database integration, authentication, and full-stack web development.

## 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

- Building web applications using Flask.
- Implementing user authentication and password hashing.
- Performing CRUD operations.
- Integrating MySQL with Python.
- Handling file uploads.
- Working with REST API concepts.
- Using Jinja2 templates for dynamic content rendering.
- Connecting frontend and backend technologies.

## 🙏 Acknowledgement

A special thanks to my mentor **Saketh Kallepu** for his valuable guidance, continuous support, and encouragement throughout the development of this project.

## 👩‍💻 Developer

**Deepika Barnikala**

Developed as part of my practical learning journey in Python Flask and Full-Stack Web Development.

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback!

**Happy Learning & Happy Coding! 🚀**
