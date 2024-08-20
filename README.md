<h1>Online Assessment System</h1><br>
<h2>Description</h2><br>
The Online Assessment System is a full-stack web application designed for creating and managing online assessments. It allows users to take quizzes, view their scores, and receive feedback. The application leverages the MERN stack (MongoDB, Express.js, React.js, Node.js) for a robust and scalable solution.
<h2>Features</h2><br>
- User registration and authentication.
- Dynamic quiz creation and management.
- Real-time score tracking and reporting.
- Secure data handling with JWT authentication.
- Responsive user interface built with React.js.
<h2>Technologies Used</h2><br>
- **MongoDB**: NoSQL database for storing user data and quiz results.
- **Express.js**: Web framework for Node.js to build RESTful APIs.
- **React.js**: Frontend library for creating an interactive and user-friendly interface.
- **Node.js**: JavaScript runtime for executing server-side code.
- **Tailwind CSS**: For attractive CSS designs.
- **Additional tools**: Node-cron for scheduling tasks, Nodemailer for email notifications.
<h2>Installation</h2><br>
<h3>Prerequisites</h3>
Ensure you have the following installed:
- Node.js (LTS version recommended)
- MongoDB (or a MongoDB Atlas account)
<h3>Setup</h3>
1. **Clone the repository:**
bash
Copy code
git clone https://github.com/chamit6450/CipherSchool.git
Install dependencies for both the server and client:

For Server:

bash
Copy code
cd Server
npm install
For Client:

bash
Copy code
cd ../Client
npm install
Setup .env file in the Server directory and add your environment variables. For example:

plaintext
Copy code
MONGO_URI=mongodb://username:password@host:port/database
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
<h2>Running the Application</h2><br>
Start the backend server:
cd Server
node index.js
The server will typically run on http://localhost:3000.

Start the frontend client:
cd ../Client
npm run dev
The client will typically run on http://localhost:5173.

<h2>Usage</h2>
Frontend: Navigate to http://localhost:5173 to access the user interface where you can take quizzes, view your results.
Backend: The server APIs are accessible at http://localhost:3000.
