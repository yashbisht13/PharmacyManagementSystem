# PharmacyManagementSystem
Automated the pharmacy’s operations, cutting inventory costs by 15% through optimized stock management. Integrated real-time analytics for monitoring sales trends and stock levels, enabling data-driven decisions that boosted profitability by 20%. This improved efficiency, reduced waste, and enhanced overall productivity.
🏥 Pharmacy Management System


🚀 Overview

The Pharmacy Management System (PMS) is an all-in-one solution for pharmacies to manage their operations. It enables smooth management of inventory, sales, prescriptions, and customer details through both web and desktop applications.

📱 Web App built with Angular for modern, dynamic user interfaces.

💻 Desktop App built with JavaFX for offline, local pharmacy management.

🔒 Backend powered by Java and Spring Boot, offering robust, secure operations.

🛠️ Tech Stack
Frontend:

Angular: SPA (Single Page Application) built with TypeScript, HTML, and CSS for a smooth, responsive UI.

Backend:

Java: Core language for implementing business logic.

Spring Boot: Robust framework for building scalable REST APIs.

Spring Security: User authentication & role-based access control.

Database:

MySQL / PostgreSQL: Reliable databases for storing all pharmacy-related data (medicines, sales, customers, etc.).

Desktop Application:

JavaFX: For creating rich, responsive desktop applications.

Scene Builder: Visual tool for designing UI layouts with JavaFX.

🏁 Installation
Prerequisites:

Before you start, ensure you have the following installed on your machine:

Java 11+ (for Spring Boot and JavaFX)

Angular CLI (for frontend development)

Node.js & npm (for managing Angular dependencies)

MySQL/PostgreSQL (for your database)

Maven/Gradle (for Java dependencies)

Scene Builder (optional, for designing JavaFX UI)

Clone the Repository:
git clone https://github.com/yourusername/pharmacy-management-system.git
cd pharmacy-management-system

Backend Setup (Spring Boot)

Go to the backend/ folder.

Modify the database credentials in src/main/resources/application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/pharmacy_management
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
spring.security.user.name=admin
spring.security.user.password=adminpassword


Build and run the backend:

./mvnw spring-boot:run

Frontend Setup (Angular)

Go to the frontend/ folder.

Install dependencies:

npm install


Run the Angular app:

ng serve


The app will be available at http://localhost:4200
.

Desktop App Setup (JavaFX)

Navigate to the desktop/ folder.

Open the project in your IDE (e.g., IntelliJ IDEA).

Run the JavaFX application to access the desktop interface for offline management.

(Optional: Use Scene Builder for a graphical UI design experience.)

🔧 Usage
Web Application

Login: Log in using admin or pharmacist credentials.

Dashboard: View an overview of sales, stock, prescriptions, and more.

Inventory Management: Add or remove medicines from stock.

Sales Transactions: Process transactions and print invoices.

Reports: Generate sales, stock, and expiry reports.

Desktop Application

Access the same features offline, including sales and inventory management, through the JavaFX desktop interface.

🤝 Contributing

We welcome contributions! Here's how you can help improve this project:

Fork the repository.

Create a new branch (git checkout -b feature-branch).

Make your changes.

Commit your changes (git commit -am 'Add new feature').

Push your branch (git push origin feature-branch).

Open a Pull Request.

Ensure your code is well-tested and adheres to the project's coding style.

📝 License

This project is licensed under the MIT License. See the LICENSE
 file for details.

👨‍💻 Authors

Yash Bisht

Aditya Gosain

Junaid Ahmed

🙏 Acknowledgments

🎉 Special thanks to JIMS Engineering Management Technical Campus
 for providing tools to enhance the system.

🌐 Huge shout-out to  both Contributors
 for making significant contributions.

And of course, you, for using or contributing to this project!
