Employee Management System

A comprehensive, full-stack web application for managing employees, departments, projects, and dependents. Built with Flask backend and vanilla HTML/CSS/JavaScript frontend, featuring an interactive dashboard with real-time analytics and CRUD operations.


## ✨ Key Features

### Dashboard
- 📊 **KPI Cards** — Real-time statistics and key metrics
- 📈 **Analytics Charts** — Donut chart (employees by department), bar chart (project budgets)
- 👥 **Recent Employees** — Quick view of latest additions

### Employee Management
- ✅ Full CRUD operations (Create, Read, Update, Delete)
- 🔍 Advanced sorting by any column
- ✏️ Inline editing (double-click to edit)
- 📋 Comprehensive employee profiles

### Department Management
- 🏢 Department creation and maintenance
- 💰 Budget tracking and management
- 📊 Live employee count per department

### Project Management
- 📝 Project tracking with status badges (Active / Completed / On Hold)
- 📅 Project timeline management
- 💵 Budget allocation and monitoring

### Dependent Management
- 👨‍👩‍👧‍👦 Link dependents to employees
- 📝 Dependent information management
- 🔗 Relationship tracking

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| **Backend** | Python 3, Flask |
| **Frontend** | HTML5, CSS3, Vanilla JavaScript |
| **Database** | SQLite |
| **Charting** | Canvas API |
| **Architecture** | Single-Page Application (SPA) |

---

## 📋 Prerequisites

- Python 3.7+
- pip (Python package manager)

---

## 🚀 Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/ShubDeshmukh2006/employeeManagementSystem.git
cd employeeManagementSystem
```

### 2. Create Virtual Environment
```bash
python -m venv venv

# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install flask
```

### 4. Run the Application
```bash
python app.py
```

### 5. Access the Application
Open your browser and navigate to:
```
http://127.0.0.1:5000
```

---

## 📁 Project Structure

```
employeeManagementSystem/
├── app.py                      # Flask application (routes & database logic)
├── requirements.txt            # Python dependencies
├── instance/
│   └── company.db              # SQLite database (auto-created)
├── templates/
│   └── index.html              # Single-page application shell
└── static/
    ├── css/
    │   └── style.css           # Global styling & dark theme
    └── js/
        └── app.js              # Frontend logic & interactivity
```

---

## 💡 Highlights & Design Decisions

- **Single-Page Application (SPA)**: Smooth user experience with client-side navigation
- **RESTful API Design**: Clean separation between frontend and backend
- **Dark Theme**: Modern, eye-friendly interface
- **Responsive Design**: Works seamlessly across devices
- **Auto-Generated Database**: Sample seed data (6 departments, 9 employees, 9 projects, 8 dependents)
- **Pure Vanilla JS**: No external frontend frameworks, demonstrating core JavaScript proficiency

---

## 🎓 Learning Outcomes

This project demonstrates:
- ✅ Full-stack web development capabilities
- ✅ Database design and SQL optimization
- ✅ RESTful API development
- ✅ Frontend UI/UX implementation
- ✅ HTML5, CSS3, and Vanilla JavaScript skills
- ✅ Python and Flask framework expertise
- ✅ Version control with Git

---

## 📊 Database Schema

The system uses SQLite with the following main tables:
- **Employees** — Employee profiles and contact information
- **Departments** — Department details with budget allocation
- **Projects** — Project information with status tracking
- **Dependents** — Employee dependent information with relationships

---

## 🎨 UI/UX Features

- Dark-themed interface for reduced eye strain
- Intuitive navigation with sidebar menu
- Inline editing for quick updates
- Real-time validation and feedback
- Responsive tables with sorting capabilities
- Visual status indicators for projects
- Interactive charts and analytics

---

## 📝 Usage Guide

1. **Dashboard** — View overall metrics and recent activities
2. **Employees** — Add new employees, edit existing records, or delete
3. **Departments** — Manage departments and their budgets
4. **Projects** — Track projects and their completion status
5. **Dependents** — Manage employee dependents and relationships

---

## 🔐 Future Enhancements

- User authentication and role-based access control
- Export functionality (PDF, CSV)
- Advanced filtering and search
- Performance metrics and reporting
- Employee leave management
- Attendance tracking

---

## 👨‍💼 About

**Developed by:** Shubham Deshmukh  
**Purpose:**  Mini Project 1 
**Year:** 2026

---

## 📄 License

This project is open source and available for educational purposes.

---

## 📧 Contact & Support

For questions or suggestions, feel free to reach out or open an issue on the repository.

---

**⭐ If you found this project helpful, please consider giving it a star!**
