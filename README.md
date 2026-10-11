# ScholarBridge – Research Opportunity Portal

A full-stack web application designed to help students discover research opportunities and enable faculty members to manage and share research projects efficiently.

## 📌 Project Overview

**ScholarBridge** is a Research Opportunity Portal developed to simplify the process of publishing, discovering, and managing university research opportunities. The platform provides an interface for viewing available projects and a REST API for creating, retrieving, updating, and deleting research opportunities.

The project demonstrates full-stack web development, RESTful API design, database integration, and CRUD operations.

## ✨ Features

- **View Research Opportunities:** Browse available research projects and their details.
- **Create Opportunities:** Add new research projects with relevant information.
- **Search and Filter:** Find opportunities by keywords, department, or status.
- **Update Opportunities:** Edit existing project information.
- **Manage Status:** Change an opportunity's status between Open and Closed.
- **Delete Opportunities:** Remove research projects when they are no longer needed.
- **REST API:** Perform CRUD operations through API endpoints.
- **Database Integration:** Store and manage opportunity records using MySQL.
- **API Testing:** Test endpoints and validate responses using Postman.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML | Web page structure |
| CSS | Styling and responsive interface |
| JavaScript | Frontend functionality |
| Node.js | Backend runtime |
| Express.js | REST API development |
| MySQL | Relational database |
| Postman | API testing |

## 📋 Research Opportunity Information

Each opportunity can include the following information:

- Opportunity ID
- Title
- Description
- Research Area
- Faculty Name
- Department
- Required Skills
- Number of Positions
- Application Deadline
- Status (Open or Closed)

## ⚙️ Getting Started

Follow these steps to run the project locally.

### Prerequisites

Make sure you have installed:

- [Node.js](https://nodejs.org/)
- [MySQL](https://dev.mysql.com/downloads/mysql/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Postman](https://www.postman.com/) (optional, for API testing)

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
cd scholarbridge-research-portal
```

Replace `YOUR_REPOSITORY_URL` with your GitHub repository URL.

### 2. Configure the Database

1. Start your MySQL server.
2. Create or import the project's database.
3. Configure the database name, username, password, and other connection settings according to the backend configuration.

**Note:** Use your project's existing SQL schema or database setup instructions. Do not commit database passwords or other sensitive credentials to GitHub.

### 3. Install Backend Dependencies

Open a terminal in the backend directory:

```bash
cd backend
npm install
```

### 4. Configure Environment Variables

If your backend uses a `.env` file, create one using the variable names expected by your database connection code.

Example:

```env
DB_HOST=localhost
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
DB_NAME=research_portal
PORT=5000
```

These are example settings. Adjust them to match your actual backend configuration. Never upload your real `.env` file.

### 5. Start the Backend Server

Check the scripts in `backend/package.json`, then run the appropriate command, for example:

```bash
npm start
```

If your project uses a different start script, use that command instead.

The API should be available at:

```text
http://localhost:5000
```

### 6. Run the Frontend

Open the frontend HTML file using Visual Studio Code's Live Server extension, or follow the frontend setup instructions included in the project.

Make sure the frontend's API base URL matches the backend server, for example:

```text
http://localhost:5000/api
```

## 🔌 API Functionality

The API supports the following operations. Confirm the exact endpoint paths against your implementation.

| Operation | HTTP Method | Purpose |
|---|---|---|
| Create opportunity | POST | Add a new research opportunity |
| Get all opportunities | GET | Retrieve the list of opportunities |
| Get opportunity by ID | GET | Retrieve a specific opportunity |
| Update opportunity | PUT | Modify opportunity details |
| Update opportunity status | PUT | Change Open/Closed status |
| Delete opportunity | DELETE | Remove an opportunity |

The API can be tested using Postman. Expected HTTP response codes include `200 OK`, `201 Created`, `400 Bad Request`, and `404 Not Found`, depending on the operation and outcome.

## 🧪 Testing

The project can be tested through:

- **Frontend testing:** Create, search, filter, edit, close, and delete opportunities.
- **API testing:** Send requests using Postman and inspect response codes and response bodies.
- **Database testing:** Verify that records are inserted, updated, and deleted correctly in MySQL.

## 🎯 Project Objectives

- Develop a functional full-stack web application.
- Implement RESTful API endpoints for CRUD operations.
- Integrate a MySQL relational database with a Node.js backend.
- Provide a simple interface for managing research opportunities.
- Practice API testing, validation, and database operations.

## 🚀 Future Improvements

- User authentication and role-based access for students and faculty.
- Student applications and application tracking.
- Faculty profiles and advanced opportunity filtering.
- Email notifications for deadlines and new opportunities.
- Deployment to a cloud hosting platform.

## 👩‍💻 Author

**Fatima Zoalfqar**

Computer Science Student  
FAST National University of Computer and Emerging Sciences


