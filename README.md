# Spirit_HACKiml_01

SpiritX_HACKtML_01
README file

Project 1 - SecureConnect



1) Instructions to run the project



1. Clone the Repository
Start by cloning the SecureConnect repository to your local machine:
git clone Randilachathuranga/Spirit_HACKtml_01
cd Spirit_HACKtml_01

2. Install Backend Dependencies
Navigate to the backend directory, then install the required npm packages.
cd secureconnect-backend
npm install

3. Set Up MongoDB
Ensure that MongoDB is installed and running on your local machine, or use MongoDB Atlas for a cloud-based database solution.
npm install --save-dev nodemon

4. Start the Backend Server
Now, start the backend server:
nodemon server.js 
By default, the server will run on http://localhost:5000.

5. Install Frontend Dependencies
Navigate to the frontend directory and install the required npm packages.
bash
cd secureconnect-frontend
npm install

6. Start the Frontend Development Server
Start the React frontend development server:
npm start
The frontend will run on http://localhost:3000.

7. Access the App
Open your browser and go to http://localhost:3000.
You should see the SecureConnect app.
Try signing up with a unique username and strong password.
After signing up, log in with your credentials to access the personalized dashboard.

8. Instructions to Sign Up to the SecureConnect
Ensure Username is at least 8 characters long and unique.
Password must contain: 
At least one lowercase letter 
At least one uppercase letter 
At least one special character



2). Database setup and configuration steps


1.MongoDB Database Dump
If you'd like to run the application with the same database as the demo, you can restore the MongoDB dump provided.

2. Download the Database Dump
- You can download the dump file from our repository .
- Or, if you want to create your own dump, follow the instructions below.

3.Restoring the Database

Step 1: Download the dump file
- Place the downloaded dump file in a directory on your local machine, e.g., `C:\mongodb-dump\`.

Step 2: Install MongoDB Locally (If Not Using MongoDB Atlas)
If the user wants to use a local MongoDB instance (instead of MongoDB Atlas), they will need to install MongoDB on their PC.
- Download MongoDB from the official MongoDB website.
- Follow the installation instructions.

Step 3 : Install MongoDB Tools (For mongodump and mongorestore)
For using commands like mongodump and mongorestore, they also need to install MongoDB Database Tools. You can download them from MongoDB Tools.

Step 4: Restore the Database
To restore the database from the dump file, use the `mongorestore` command:
   1. Open a terminal/command prompt.
   2. Run the following command:
   mongorestore --uri="mongodb+srv://your-mongo-connection-string" --dir="C:\mongodb-dump"


Any assumptions made during development 

User Feedback & Error Handling: Clear user messages and effective error management.
Testing & Reliability: Thorough testing for functionality and performance.
Security & Logging: Proper error logging and secure operations.
Cross-Browser & Performance: Optimized for speed and compatibility across browsers.


Additional features implemented

JWT tokens are used for Authentication and Authorisation. Those tokens are only valid for an hour.
Secured system. Passwords are hashed.
Responsive.  
All the Data gathered in this system is encrypted.
Only Users who have access privileges can login to the system because of the JWT tokens.
