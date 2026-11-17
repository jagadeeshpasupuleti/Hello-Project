# JobSphere – Job Seeker and Recruiter Platform

JobSphere is a web-based job portal designed to connect job seekers with recruiters through a single platform. It allows candidates to explore job opportunities, manage their profiles, and apply for jobs, while recruiters can manage job postings and applications.

The main idea behind this project is to make the job search and recruitment process easier and more accessible.

## Features

- User registration and login
- JWT-based authentication
- Job posting and management
- Browse available job opportunities
- Apply for jobs
- Prevent duplicate job applications
- Manage candidate profile and skills
- Store and manage application data using MongoDB

## Technologies Used

**Backend**
- Java
- Spring Boot
- Spring Web
- Spring Data MongoDB
- Spring Security / JWT

**Database**
- MongoDB Atlas

**Tools**
- Maven
- Git
- GitHub
- Postman

## Project Structure

The backend is organized into separate packages based on functionality:

- `controller` – Handles incoming API requests.
- `repository` – Communicates with the database.
- `model` – Contains application data models.
- `service` – Handles business logic.
- `security` – Manages authentication and JWT-related functionality.

## API Modules

| Module | Description |
|---|---|
| Authentication | User registration and login |
| Jobs | Create, view and manage job postings |
| Applications | Apply for jobs and manage applications |
| Profile & Skills | Manage candidate profile information |

## Database

MongoDB Atlas is used to store user details, job information, applications, and profile data.

## Running the Project Locally

1. Clone the repository:

   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Open the project in your IDE.

3. Configure your MongoDB Atlas connection and required application settings.

4. Run the application:

   ```bash
   ./mvnw spring-boot:run
   ```

   On Windows:

   ```bash
   mvnw.cmd spring-boot:run
   ```

5. Once the application starts, the backend will be available at:

   `http://localhost:8080`

## Future Improvements

- AI-based job recommendations
- Resume analysis and skill matching
- Advanced job search and filtering
- Recruiter dashboard
- Email notifications
- Application status tracking

## Project Goal

To build a practical recruitment platform that simplifies the interaction between job seekers and recruiters, with scope for adding intelligent features in the future.
