AI Study Buddy

Project Description

AI Study Buddy is an intelligent learning application designed to help students improve their learning experience. It provides a platform to organize study materials, manage notes, and support quiz-based learning. The application uses MongoDB to store student and study-related information.

Objectives

- To help students organize their study materials.
- To store and manage study notes.
- To provide quiz-based learning support.
- To maintain student information securely.
- To make learning easier and more efficient.

Technologies Used

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB
- Database Connectivity: Mongoose
- Development Tool: Visual Studio Code

Project Structure

AI-Study-Buddy/
├── server.js
├── database.js
├── .env
├── package.json
├── models/
├── routes/
└── README.md

Installation

Step 1: Install Dependencies

npm install express mongoose dotenv cors

Step 2: Configure MongoDB

Create a ".env" file and add:

PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/ai_study_buddy

Step 3: Connect Database

Create a "database.js" file to connect the Node.js application to MongoDB using Mongoose.

Step 4: Run the Application

node server.js

Database

Database Name: "ai_study_buddy"

MongoDB can store student details, study notes, learning materials, and quiz results.

Expected Output

- Successful MongoDB database connection.
- Backend server running on port 5000.
- Students can access the learning application when the required frontend and backend features are implemented.

Future Enhancements

- AI-powered study recommendations.
- Automatic quiz generation.
- Personalized learning plans.
- Chatbot for student questions.
- Progress tracking and performance reports.

Conclusion

AI Study Buddy aims to provide a convenient and organized learning environment for students. By integrating a web application with a MongoDB database, the project can support study material management and future AI-based learning features.

Author

B.Sc. Computer Science (AI & Data Science) – Final Year Project
