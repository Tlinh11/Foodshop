# Foodshop
**Technologies Used**
Frontend (React Native):
UI development for Android devices.
Utilizes libraries such as Ant Design Mobile and React Native Paper.
Backend (Spring Boot & Java):
RESTful API to handle business logic and user requests.
Integrated with Spring Security for authentication and role-based access.
Database (SQL Server):
Stores menu, orders, users, and revenue data.
Includes stored procedures and triggers for real-time inventory management.
Setup Instructions
Clone the repository:
git clone https://github.com/your-username/restaurant-management-app.git
**Backend Setup:**
Navigate to the backend directory and build the Spring Boot project:
cd backend
./mvnw spring-boot:run
Configure your SQL Server connection in application.properties.
**Frontend Setup:**
Navigate to the frontend directory and install dependencies:
cd frontend
npm install
**Run the React Native app:**
npx react-native run-android
**Database:**
Set up SQL Server and execute the provided database schema and initial data files.
