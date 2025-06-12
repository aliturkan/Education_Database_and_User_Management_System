<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Education Database and User Management System</title>
</head>
<body>

    <h1>Education Database and User Management System</h1>

    <h2>Overview</h2>
    <p>This project implements an Education Database and User Management System, designed to manage educational institution data and user information efficiently.</p>

    <h2>Features</h2>
    <ul>
        <li><strong>Database Management</strong>: Utilizes PostgreSQL for storing and managing educational data.</li>
        <li><strong>User Authentication</strong>: Implements secure user authentication and access control.</li>
        <li><strong>User Management</strong>: Provides functionalities for managing user accounts and roles.</li>
        <li><strong>Data Integration</strong>: Supports integration with other educational systems through APIs.</li>
        <li><strong>Admin Dashboard</strong>: Includes an admin dashboard for system management and monitoring.</li>
    </ul>

    <h2>Technologies Used</h2>
    <ul>
        <li><strong>Java</strong>: Core programming language.</li>
        <li><strong>Spring Boot</strong>: Framework for building and running Java applications.</li>
        <li><strong>Spring Security</strong>: Provides authentication and access control.</li>
        <li><strong>PostgreSQL</strong>: Relational database management system.</li>
        <li><strong>Hibernate</strong>: Object-relational mapping tool for the Java programming language.</li>
        <li><strong>Maven</strong>: Dependency management.</li>
        <li><strong>JUnit</strong>: Unit testing framework.</li>
        <li><strong>RESTful APIs</strong>: For data integration and communication with other systems.</li>
    </ul>

    <h2>Installation</h2>
    <ol>
        <li>Clone the repository:
            <pre>git clone https://github.com/aliturkan/Education_Database_and_User_Management_System.git</pre>
        </li>
        <li>Navigate into the project directory:
            <pre>cd Education_Database_and_User_Management_System</pre>
        </li>
        <li>Configure PostgreSQL database:
            <ul>
                <li>Create a database named <code>education_db</code>.</li>
                <li>Update <code>application.properties</code> with your database credentials.</li>
            </ul>
        </li>
        <li>Build and run the application using Maven:
            <pre>mvn spring-boot:run</pre>
        </li>
        <li>Access the application at <a href="http://localhost:8080">http://localhost:8080</a>.</li>
    </ol>

    <h2>Usage</h2>
    <ul>
        <li><strong>User Management</strong>: Use the provided API endpoints or admin dashboard to create, update, and delete user accounts.</li>
        <li><strong>Database Operations</strong>: Perform CRUD operations on educational data stored in PostgreSQL.</li>
        <li><strong>Authentication</strong>: Test authentication and authorization features using provided endpoints.</li>
    </ul>

    <h2>Contributing</h2>
    <p>Contributions are welcome! Feel free to fork the repository and submit pull requests for new features, improvements, or bug fixes.</p>

    <h2>Contact</h2>
    <p>For questions or inquiries, please contact author Ali Turkan at <a href="mailto:aliturkan@gmail.com">aliturkan@gmail.com</a>.</p>

    <h2>POSTMAN API</h2>
    <p>For API documentation and examples, check out the <a href="https://api.postman.com/collections/13053376-9b260cc3-c29f-4049-bea9-6e2077d7fdc6?access_key=PMAT-01H3J3CQRFMVZZSWHEJJ9AAD03">Postman Collection</a>.</p>

</body>
</html>
