📦 Prerequisites
Java 8 or higher
Maven 3.x

MySQL Server

IDE (IntelliJ, Eclipse, or VS Code)

🛠️ Setup Instructions
1. Clone the project
bash
git clone https://github.com/Mebaid10902/TaskFlow-Task-Management-Web-Application
cd taskflow
2. Create the MySQL Database
Open your MySQL client and run:

sql

CREATE DATABASE users_database;
⚠️ Make sure your MySQL server is running and accessible at localhost:3306.

3. Configure database credentials
In src/main/resources/application.properties, check/update:

properties
spring.datasource.url = jdbc:mysql://localhost:3306/users_database?useSSL=false
spring.datasource.username = root
spring.datasource.password = root
You can use environment variables instead for security.
▶️ Run the Application
Using IDE:
Open the project in your IDE.

Run the main() method from TodoManagementApplication.java.

Using Terminal:
bash
mvn spring-boot:run
🌐 Access the App
Once the app is running, open your browser:

http://localhost:8080/

🐳 Docker Support (Optional)
1. Dockerfile
2. Docker-compose
