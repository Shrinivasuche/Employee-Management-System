🚀 Employee Management System
* Full-Stack Web Application using React JS, Spring Boot & MySQL
* This is a complete Employee Management System (EMS) built using React (Vite) for the frontend, Spring Boot for the backend, and MySQL as the database.
It provides a clean interface to view, create, update, and delete employees.

📌 Frontend (Local URLs)
Feature	URL
🧾 List Employees	http://localhost:5173/
➕ Add Employee	http://localhost:5173/add-employee
✏️ Update Employee	http://localhost:5173/update-employee/:id

📁 GitHub Repository:
🔗 https://github.com/Shrinivasuche/Employee-Management-System

✨ Features:
👨‍💼 Employee CRUD Operations
View all employees
Add new employee
Edit existing employee
Delete employee
Auto-update list after actions

💾 Backend Capabilities
REST API using Spring Boot
JPA + Hibernate for database operations
MySQL database integration

🌐 Frontend
React (Vite)
React Router DOM
Axios for API calls
Bootstrap styling

🛠️ Tech Stack
Frontend:
React JS
Vite
React Router
Bootstrap
Axios

Backend:
Spring Boot
Spring Data JPA
REST API
MySQL

⚙️ Setup Instructions
▶️ 1. Backend Setup
cd ems-backend
mvn spring-boot:run

Backend runs on:
👉 http://localhost:8080


▶️ 2. Frontend Setup
cd ems-fullstack
npm install
npm run dev

Frontend runs on:
👉 http://localhost:5173


📡 API Endpoints (Spring Boot)
Method	         Endpoint	                     Description
GET	        /api/emp/employees	          Fetch all employees
POST	      /api/emp/create	              Add new employee
GET	        /api/emp/{id}	                Get employee by ID
PUT	        /api/emp/update/{id}	        Update employee
DELETE	    /api/emp/delete/{id}	        Delete employee
GET	        /api/emp/email-id/{email}	    Search employee by email


🚧 Future Enhancements
Employee search (name/email)
Pagination & sorting
Login system (JWT authentication)
Department/role management
Improved UI layout


👤 Author
Shrinivas Uche
Full-Stack Developer (React + Java Spring Boot)
