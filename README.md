# TuLaBy - FCI Sohag Graduation Project

TuLaBy is a comprehensive educational platform developed as a graduation project for the Faculty of Computer Information and Artificial Intelligence (FCI) at Sohag University. This platform aims to revolutionize the learning experience for students and streamline administrative tasks for instructors, bringing modern convenience and efficiency to academic management.

## Table of Contents
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Technical Stack](#technical-stack)
- [System Architecture](#system-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Live Links](#live-links)

## Project Overview
TuLaBy provides a centralized system for managing attendance, sharing study resources, facilitating student engagement, and administering online assessments. The platform includes both web and mobile applications to maximize accessibility for students and instructors.

## Key Features
- **Seamless Attendance Management**: Enables automated attendance tracking using QR codes or OTP, making attendance simple and efficient.
- **Dynamic Q&A Section for Enhanced Student Interaction**: Encourages collaborative learning with a dedicated section for questions and answers, allowing students to engage more deeply with the course material.
- **Diverse Study Resources for Effective Learning**: Instructors can enrich the learning process by offering various study resources, helping students access relevant materials directly within the platform.
- **Online Examinations for Modern Assessment**: Modernizes assessments by enabling the creation and management of online exams, providing students with a flexible and contemporary testing experience.

## Technical Stack
- **Frontend**: HTML, CSS, JavaScript, and React for an interactive web interface.
- **Backend**: ASP.NET for robust server-side logic and API development.
- **Database**: SQL Server for efficient and secure data storage.
- **Mobile App**: Developed with Dart and Flutter for cross-platform compatibility.
- **UI/UX**: Figma for an intuitive, responsive interface.

## System Architecture
The system architecture includes:
1. **Data Flow Diagrams (DFDs)** for mapping data movement and processing.
2. **Entity-Relationship Diagrams (ERDs)** for database design, involving entities such as Students, Professors, Courses, and Attendance Records.

## Installation

### Prerequisites
- [.NET Core SDK](https://dotnet.microsoft.com/download)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) for frontend dependencies.
- [Flutter SDK](https://flutter.dev/docs/get-started/install) for mobile app development.

### Steps
1. **Clone the Organization**:  
   **_Note:_** This repository is currently unavailable publicly. Ensure you have access to the repository link or request it from the project maintainers.
   ```bash
   # Example command (update with the actual link once available)
   git clone https://github.com/TuLaBy-LLC/TuLaBy.git
   cd TuLaBy

2. **Backend Setup**:
   - Navigate to the backend project directory:
     ```bash
     cd TuLaBy-Backend
     ```
   - Update the `appsettings.json` file with your SQL Server connection string.
   - Run migrations to set up the database:
     ```bash
     dotnet ef database update
     ```
   - Start the backend server:
     ```bash
     dotnet run
     ```

3. **Frontend Setup**:
   - Navigate to the frontend project directory:
     ```bash
     cd TuLaBy-Frontend
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Start the frontend server:
     ```bash
     npm run dev
     ```

4. **Mobile App Setup**:
   - Open the Flutter project directory:
     ```bash
     cd TuLaBy-Mobile
     ```
   - Install dependencies and run the app:
     ```bash
     flutter pub get
     flutter run
     ```

## Usage
1. Access the web application(Dashboard) via `https://tulaby.runasp.net/`.
2. Log in as an admin, professor, or Instructor to explore specific functionalities.
3. The mobile app is available for Android and iOS devices, offering a seamless experience for students and faculty.

## Contributing
We welcome contributions! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeature
3. Commit your changes:
   ```bash
   git commit -m "Add new feature: YourFeature"
4. Push to the branch:
   ```bash
   git push origin feature/YourFeature
5. Create a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Live Links

- **Dashboard**: [TuLaBy Dashboard](https://tulaby.runasp.net/)
- **WebAPI**: [TuLaBy WebAPI](https://tulaby-api.runasp.net/)
- **WebAPI**: [TuLaBy Front-End (Student Platform)](https://tulaby.netlify.app/)
