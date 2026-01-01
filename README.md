# 🚀 User CRUD Application with Spring Boot and React

A full-stack CRUD (Create, Read, Update, Delete) application built with Spring Boot backend and React frontend. This project demonstrates a complete user management system with modern UI and RESTful API integration.

## 🎯 Features
 
- ✨ User registration and management
- 🔐 Secure authentication
- 📱 Responsive design 
- 🔄 Real-time data updates
- 🎨 Modern UI with Material-UI     
- 📊 Form validation       
- 🔍 Search and filter capabilities   
 
## 🛠️ Tech Stack 

### Backend
- ☕ Java 17
- 🌱 Spring Boot 3.x
- 🗄️ MySQL Database
- 🔒 Spring Security
- 📦 Maven

### Frontend
- ⚛️ React 18
- 🎨 Material-UI
- 🔄 Axios for API calls
- 📱 Responsive Design
- 🎯 TypeScript

## 📁 Project Structure

```
📦 user-crud-springboot-react
 ┣ 📂 backend
 ┃ ┣ 📂 src
 ┃ ┃ ┣ 📂 main
 ┃ ┃ ┃ ┣ 📂 java
 ┃ ┃ ┃ ┃ ┗ 📂 com
 ┃ ┃ ┃ ┃ ┃ ┗ 📂 example
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂 backend
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂 controller
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📄 UserController.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂 config
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📄 JacksonConfig.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂 exception
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📄 UserNotFoundException.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📄 UserNotFoundAdvice.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂 model
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📄 User.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂 repository
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📄 UserRepository.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂 service
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📄 UserService.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📄 BackendApplication.java
 ┃ ┃ ┃ ┣ 📂 resources
 ┃ ┃ ┃ ┃ ┗ 📄 application.properties
 ┃ ┃ ┗ 📂 test
 ┃ ┣ 📄 pom.xml
 ┃ ┣ 📄 mvnw
 ┃ ┗ 📄 mvnw.cmd
 ┃
 ┣ 📂 frontend
 ┃ ┣ 📂 src
 ┃ ┃ ┣ 📂 users
 ┃ ┃ ┃ ┣ 📄 AddUser.js
 ┃ ┃ ┃ ┣ 📄 EditUser.js
 ┃ ┃ ┃ ┗ 📄 ViewUser.js
 ┃ ┃ ┣ 📂 pages
 ┃ ┃ ┃ ┗ 📄 Home.js
 ┃ ┃ ┣ 📂 layout
 ┃ ┃ ┃ ┗ 📄 Navbar.js
 ┃ ┃ ┣ 📄 App.js
 ┃ ┃ ┣ 📄 App.css
 ┃ ┃ ┣ 📄 App.test.js
 ┃ ┃ ┣ 📄 index.js
 ┃ ┃ ┣ 📄 index.css
 ┃ ┃ ┣ 📄 logo.svg
 ┃ ┃ ┣ 📄 reportWebVitals.js
 ┃ ┃ ┗ 📄 setupTests.js
 ┃ ┣ 📂 public
 ┃ ┃ ┣ 📄 index.html
 ┃ ┃ ┃ ┣ 📄 favicon.ico
 ┃ ┃ ┃ ┣ 📄 manifest.json
 ┃ ┃ ┃ ┣ 📄 robots.txt
 ┃ ┃ ┃ ┣ 📄 logo192.png
 ┃ ┃ ┃ ┗ 📄 logo512.png
 ┃ ┣ 📄 package.json
 ┃ ┗ 📄 tsconfig.json
 ┃
 ┗ 📄 README.md
```

## 🚀 Getting Started

### Prerequisites
- Java 17 or higher
- Node.js 16 or higher
- MySQL 8.0 or higher
- Maven 3.6 or higher

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Configure database in `application.properties`
3. Run the Spring Boot application:
   ```bash
   ./mvnw spring-boot:run
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

## 🧪 Testing
- Backend tests: `./mvnw test`
- Frontend tests: `npm test`

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- **Hariharan S** - *Initial work* - [HARIHARANS24](https://github.com/HARIHARANS24)

## 🙏 Acknowledgments

- Spring Boot Team
- React Team
- Material-UI Team
- All contributors and supporters 
