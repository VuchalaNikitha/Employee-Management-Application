# Employee Management System using Angular, Spring Boot, and MySQL Full Stack Project

The Employee Management System is a comprehensive web application designed to streamline and enhance the management of employee-related tasks within an organization. This system utilizes a modern and efficient technology stack, including Spring Boot for the backend, Angular for the frontend, and MySQL for the database.

## Technology Stack

### Backend:
- **Spring Boot:** The backend of the Employee Management System is built using Spring Boot, a Java-based framework known for its simplicity and ease of use. Spring Boot provides a robust and scalable foundation for developing enterprise-level applications.

- **MySQL:** The database layer is powered by MySQL, a reliable relational database management system. MySQL is utilized for storing and retrieving employee-related data, ensuring data integrity and efficiency in data management.

### Frontend:
- **Angular:** The frontend of the application is developed using Angular, a powerful and dynamic front-end framework. Angular facilitates the creation of a responsive and interactive user interface, enabling seamless communication with the backend.

---

## Key Features

1. **Home Page:**
   - The home page serves as the central hub, providing users with an intuitive and user-friendly interface. It includes quick links to essential features and announcements.

2. **View All Employees:**
   - Users can easily access a comprehensive list of all employees within the organization. The interface allows for efficient sorting, searching, and filtering of employee data.

3. **Add Employee Page:**
   - The system offers a dedicated page for adding new employees, featuring a well-designed form with form validation. This ensures that accurate and complete information is entered for each employee.

4. **CRUD Operations:**
   - The system supports all essential CRUD (Create, Read, Update, Delete) operations. Users can add new employees, update existing records, delete unnecessary entries, and view detailed information about each employee.

5. **Form Validation:**
   - Robust form validation mechanisms are implemented to ensure the accuracy and completeness of data entered by users. This helps in maintaining data integrity and consistency.

---

## How to Run the Project

### Backend (Spring Boot Application)
1. Clone the repository.
2. Open the project in your preferred IDE (e.g., IntelliJ, Eclipse, VS Code).
3. Navigate to the `src/main/resources` folder and locate the `application.properties` file.
4. Update the following credentials in `application.properties` with your MySQL database details:

```
spring.datasource.url=jdbc:mysql://localhost:3306/<your-database-name>
spring.datasource.username=<your-database-username>
spring.datasource.password=<your-database-password>
```

5. Run the Spring Boot application using:
   ```bash
   ./mvnw spring-boot:run   # For Maven users
   ./gradlew bootRun         # For Gradle users
   ```

6. The backend will run by default on `http://localhost:8080`.

---

### Frontend (Angular Application)
1. Navigate to the Angular project folder.
2. Install dependencies by running:
   ```bash
   npm install
   ```
3. Start the Angular development server with:
   ```bash
   npm start
   ```
4. The frontend will run by default on `http://localhost:4200`.

---

## Conclusion
The Employee Management System offers a robust solution for organizations to efficiently manage their workforce. The use of Spring Boot, Angular, and MySQL ensures a scalable, secure, and user-friendly platform for handling various employee-related tasks.