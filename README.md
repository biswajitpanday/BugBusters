# BugBusters

BugBusters is a private developer panel for internal issue tracking and collaboration within companies. It serves as a secure, company-specific alternative to public platforms like StackOverflow, enabling employees to share issues, provide solutions, and engage in community-driven problem-solving.

---

![Landing Page](BugBustersLanding.png)

## Why This Project?

### 1. Solving Real-World Problems
BugBusters addresses the need for private, company-specific developer collaboration, offering a secure alternative to public platforms like StackOverflow. It ensures sensitive data and internal discussions remain confidential.

### 2. Comprehensive Full-Stack Implementation
This project showcases a well-rounded full-stack application, combining:  
- A **scalable backend** built with **ASP.NET Core** using best practices like Clean Architecture and Repository Pattern.  
- A **modern React-based frontend** with a polished user interface and seamless user experience.

### 3. Demonstration of Key Software Engineering Skills
- **System Design**: Designed with clean separation of concerns, modular architecture, and scalability in mind.  
- **Database Design**: Features optimized database schema using **Entity Framework Core** with migrations and seed data.  
- **Role-Based Access Control**: Implemented secure role-based access for Admins, Moderators, and Users.  
- **API Documentation**: Includes detailed Swagger API documentation for easy integration and testing.  
- **Frontend Engineering**: Demonstrates reusable React components, state management, and responsive design.

### 4. End-to-End Project Development
This project demonstrates proficiency in the entire software development lifecycle:  
- **Requirement Analysis**: Designed features based on real-world use cases.  
- **Implementation**: Developed scalable, production-ready client and server applications.  
- **Testing**: Comprehensive unit and integration testing for backend logic and frontend UI.  
- **Deployment (Optional)**: Can be hosted on modern platforms for live demos.

### 5. Industry-Relevant Tech Stack
This project utilizes technologies commonly used in professional software development, including:  
- **Backend**: ASP.NET Core 7, JWT Authentication, SQL Server, Serilog.  
- **Frontend**: React, TypeScript, React Query, Sass, Bootstrap.  
- **Tools**: Git, GitHub Actions, Jest, and more.

---

## Key Achievements

1. **Role-Based User Management**: Implemented secure and efficient user authentication with JWT and role-based access control for Admins, Moderators, and Users.  
2. **Dynamic Q&A System**: Built a robust question-and-answer platform with upvote/downvote functionality and admin approval workflows.  
3. **Responsive UI**: Delivered a mobile-friendly, responsive design using Sass, Bootstrap, and modern React best practices.  
4. **Scalable Backend**: Architected the backend with modular layers, including API, Service, and Repository layers, adhering to Clean Architecture principles.  
5. **Comprehensive Testing**: Achieved high code coverage with **unit tests** (NUnit, Moq) and **frontend tests** (Jest, Testing Library).  
6. **API Documentation**: Delivered a well-documented API using Swagger, facilitating easy integration and testing.  
7. **Project Management**: Maintained a clean Git workflow with well-organized commits, branching, and detailed documentation.

---

## Overview

This portfolio showcases the two major components of the BugBusters project:

1. **[BugBusters Server](https://github.com/biswajitpanday/BugBusters.Server)**: The backend API built with ASP.NET Core, supporting robust functionalities like user management, Q&A systems, and role-based access control.
2. **[BugBusters Client](https://github.com/biswajitpanday/BugBusters.Client)**: The frontend application developed with React, offering an intuitive and responsive user interface for users to interact with the system.

---

## Screenshots

### BugBusters Client (Screenshots)
- **Question List Page**  
  ![Question List](https://github.com/biswajitpanday/BugBusters.Client/blob/master/screenshots/question-list.png)

- **Question and Answer Page**  
  ![Q&A Page](https://github.com/biswajitpanday/BugBusters.Client/blob/master/screenshots/question-description.png)

### BugBusters Server (Swagger API)
- **Swagger**
![Swagger Screenshot](https://github.com/biswajitpanday/BugBusters.Server/blob/master/swagger-screenshot.png)

---

## Features

- **User Management**: Registration, login, and profile management.  
- **Roles**: Role-based access control for Admins, Moderators, and Users.  
- **Q&A System**: Ask questions, provide answers, upvote/downvote content, and admin approval workflows.  
- **Search and Navigation**: Advanced search and easy navigation for browsing topics.

---

## Technology Stack

### Backend
- ASP.NET Core 7
- Entity Framework Core (Code First, Migrations)
- SQL Server
- JWT Authentication
- Serilog
- AutoMapper
- NUnit and Moq for Testing

### Frontend
- React 18
- TypeScript
- React Query and Context API
- Sass and Bootstrap
- React Router DOM
- Jest and Testing Library

---

## Getting Started

### Prerequisites

- .NET 7 SDK
- SQL Server
- Node.js (v16 or later)
- npm or yarn

### Setup Instructions

#### Backend
1. Clone the server repository:
   ```bash
   git clone https://github.com/biswajitpanday/BugBusters.Server.git
   ```
2. Navigate to the solution directory:
   ```bash
   cd BugBusters.Server
   ```
3. Restore dependencies:
   ```bash
   dotnet restore
   ```
4. Apply database migrations:
   ```bash
   dotnet ef database update
   ```
5. Run the server:
   ```bash
   dotnet run
   ```

#### Frontend
1. Clone the client repository:
   ```bash
   git clone https://github.com/biswajitpanday/BugBusters.Client.git
   ```
2. Navigate to the project directory:
   ```bash
   cd BugBusters.Client
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Run the application:
   ```bash
   npm start
   ```

---

## Contributing

We welcome contributions! Please follow these steps:
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For questions or support, please contact the repository maintainer at biswajitmailid@gmail.com.
