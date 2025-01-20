# Job Portal Application using Java Spring Framework

## 📖 Project Overview

This project is a **Job Portal Application** built using the **Java Spring Framework**. The application facilitates efficient job posting and searching functionalities by providing CRUD (Create, Read, Update, Delete) operations for job listings and user profiles. It is integrated with **MySQL** for persistent data storage and tested extensively using **Postman**.

---

## 🛠️ Key Features

### 1️⃣ User Management:
- **User Registration**: Secure user registration functionality with role-based access (e.g., Job Seeker, Employer).
- **Login**: Secure authentication using Spring Security.

### 2️⃣ Job Listings Management:
- **Add Job**: Employers can post new job openings.
- **Search Jobs**: Job seekers can search job listings with filters like job title, location, and salary range.
- **Update Job**: Employers can update existing job postings.
- **Delete Job**: Employers can remove outdated job postings.

### 3️⃣ REST API Endpoints:
- `@PostMapping("/users/register")`: Register a new user.
- `@PostMapping("/jobs")`: Add a new job posting.
- `@GetMapping("/jobs")`: Fetch all job postings.
- `@GetMapping("/jobs/{id}")`: Fetch job details by ID.
- `@PutMapping("/jobs")`: Update complete job details.
- `@DeleteMapping("/jobs/{id}")`: Delete a job posting by ID.

---

## ⚙️ Technical Stack

### Backend:
- **Java**: Core language for application logic.
- **Spring Boot**: Simplifies application development and setup.
- **Spring Framework**: Manages dependency injection and application context.
- **Spring Security**: Provides authentication and role-based authorization.
- **Spring Data JPA**: For seamless database interaction.

### Database:
- **MySQL**: Relational database for persistent data storage.

### Tools:
- **Postman**: For API testing and debugging.
- **Maven**: Dependency management and project build tool.

---

## 🔧 Implementation Details

### 1. Configuration Class:
- Set up MySQL database connections and JPA configurations.

### 2. Controller Class:
- Contains RESTful API endpoints for job and user management.

### 3. Service Class:
- Handles business logic and interacts with DAO layer.

### 4. DAO (Data Access Object):
- Uses Spring Data JPA to perform database operations.

### 5. Testing:
- Verified all endpoints using Postman for seamless integration and functionality.

---

## 🚀 How to Run the Project

### Clone the Repository:
```bash
git clone <repository_url>
```

### Navigate to the Project Directory:
```bash
cd <project_directory>
```

### Configure the MySQL Database:
- Update the `application.properties` file with your MySQL database credentials:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/job_portal_db
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

### Build the Project:
```bash
mvn clean install
```

### Run the Application:
```bash
mvn spring-boot:run
```

### Access the Application:
- API endpoints can be tested via Postman or accessed at `http://localhost:8080`.

---

## 🌟 Outcomes
- Developed a functional job portal application using Java Spring Framework.
- Successfully integrated MySQL for robust and persistent data storage.
- Enhanced understanding of REST API development and Spring Security.

---

## 📂 Folder Structure
```
project-directory/
|
├── src/main/java/com/example
│   ├── config/        # Configuration classes
│   ├── controller/    # Controller classes
│   ├── dao/           # Data Access Objects
│   ├── model/         # Entity classes
│   ├── service/       # Business logic
|
├── src/main/resources
│   ├── application.properties  # Application configuration
│   └── data.sql                # Initial test data (if any)
|
├── pom.xml          # Maven dependencies
└── README.md        # Project documentation
```

---

## 🌐 GitHub Repository
The full source code for this project is available here: [GitHub Repository](https://github.com/Shravan0715)

---

## 📞 Contact
Feel free to reach out for collaboration or queries:
- **Email**: [shravangalagali573@gmail.com](mailto:shravangalagali573@gmail.com)
- **LinkedIn**: [Shravan S. Galagali](https://www.linkedin.com/in/shravan-s-galagali-15559a226/)

---

Thank you for exploring the project! 😊

