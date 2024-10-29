 Online Complaint Registration System

Objective:
Create a web application for users to register and track complaints, providing a centralized platform for effective complaint management.

Project Features:
1. Registration and Login
2. Profile Management
3. Complaint Registration (with categories and descriptions)
4. Complaint Status Tracking
   
Admin Module:

1. Complaint Management (view, assign, resolve, close)
2. User Management (view, edit, delete)
3. Dashboard (complaint statistics, user insights)
4. Reporting (generate reports on complaints)

Complaint Module:

1. Complaint Listing (filterable by status, category)
2. Complaint Details (view, edit, delete)
3. Complaint Assignment (to administrators or support staff)
4. Complaint Resolution and Closure

Database Schema:

users:
  - _id (ObjectId)
  - name (String)
  - email (String)
  - password (String)

complaints:
  - _id (ObjectId)
  - title (String)
  - description (String)
  - category (String)
  - status (String)
  - assignedTo (ObjectId, ref: users)
  - userId (ObjectId, ref: users)

admins:
  - _id (ObjectId)
  - name (String)
  - email (String)
  - password (String)
    
Tools and Technologies:

1. MongoDB Compass
2. Postman
3. Visual Studio Code
4. Node.js
5. Express.js
6. React.js
   
This project  provides a solid foundation for building an Online Complaint Registration System using MERN Stack.
