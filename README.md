
# College Management System

The College Management System is a MERN Stack-based system with three different login portals for students, faculty, and admin.

## Tech Stack

**Client:** React, Redux, TailwindCSS

**Server:** Node, Express

**Database:** MongoDB

## Student Features

- Internal Marks: Access to view internal marks for courses
- External Marks: Access to view external marks for courses
- Course Materials: Ability to download course materials
- Notices: Access to view notices
- Timetables: Access to view their own timetables
- Password Update: Ability for students to update their passwords

## Faculty Features

- Student Details: Ability for faculty to view student details
- Password Update: Ability for faculty to update their own passwords
- Notices: Ability for faculty to add notices
- Materials Upload: Ability for faculty to upload course materials
- Timetable Management: Ability for faculty to manage timetables
- Exam Mark Recording: Ability for faculty to record internal and external exam marks

## Admin Features

- Account Creation: Ability for admins to add new students, faculty, and admin accounts
- Account Details Modification: Ability for admins to modify the details of each account
- Subject Management: Ability for admins to add/edit subjects
- Notices Management: Ability for admins to add/edit notices

## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone   https://github.com/karansarda121/college_management_system.git
   ```

2. **Install dependencies:**

   ```bash
   cd backend
   npm install
   cd ../frontend
   npm install
   ```

3. **Setup environment variables:**
4. 
  - ## In frontend
   .env   
      REACT_APP_APILINK = http://localhost:5000/api
       REACT_APP_MEDIA_LINK = http://localhost:5000/media

  - ## In backend
  .env
   MONGODB_URI =mongodb+srv://20ucs093:123456karan@cluster0.xsrq2e6.mongodb.net/? 
    retryWrites=true&w=majority&appName=Cluster0
   PORT = 5000
   FRONTEND_API_LINK = http://localhost:3000

4. **Run the admin seeder:**

   ```bash
   cd backend
   npm run seed
   ```

   - **Login ID:** `123456`
   - **Password:** `admin123`
  
   - Using this login to the admin account and from admin you can add new faculty, student and admins!

5. **Run the backend server:**

   ```bash
   cd backend
   npm start
   ```

6. **Run the frontend server:**

   ```bash
   cd ../frontend
   npm start
   ```


