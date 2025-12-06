SCHEDULE SYSTEM
Overview

Schedule System is a web application designed to automate and manage design tasks for a creative company.

It allows Admins to assign clients and weekly design schedules, and Users (Designers) to mark task completion. The system tracks task completion for posters and reels and provides a monthly summary for each client.

This system is perfect for design teams in small to medium-sized companies to streamline task allocation, track productivity, and maintain clear records of work delivered.

🔗 Live Site: https://schedulesystem.netlify.app/
```
```
🎯 Project Purpose

Traditional task management methods—like Excel sheets, WhatsApp messages, or physical notes—are inefficient and error-prone.

Schedule System introduces:

✅ Structured weekly schedules per client
✅ Task completion marking by Users
✅ Automatic monthly summaries for Admins
✅ Multi-client handling for each designer
✅ Digital tracking of posters and reels delivered

```
```
🧩 SYSTEM ROLES AND STRUCTURE
🧍‍♂️ User (Designer)

User Actions:

Login to the system.
View assigned clients and their weekly schedule.
Mark tasks as completed per client (poster or reel).
See schedule and task history per client.

👨‍💼 Admin

Admin Actions:

Login as Admin.
Add clients and assign weekly schedules (3 posters + 1 reel).
Track task completion per user and client.
View monthly summary: how many posters and reels were completed per client.
```
```
⚙️ HOW THE SYSTEM WORKS (Step-by-Step Workflow)
🧾 Step 1: Registration/Login

Both Admin and Users log in through the authentication system.

Users: Can see their assigned clients and weekly schedule.
Admin: Can assign clients, schedule tasks, and view summaries.
```
```
🏢 Step 2: Client & Schedule Management (Admin Panel)

The Admin can:

Add new clients with name and details.
Assign weekly schedules per client (3 posters + 1 reel per week).
Update schedules as needed.
Monitor all users’ task completion.
```
```
📅 Step 3: Task Completion (User Panel)

Users can:

View all assigned clients.
For each client, mark tasks as Poster Done or Reel Done for specific dates.
System automatically stores task completion in the backend database (MongoDB).
```
```
📊 Step 4: Monthly Summary

At the end of each month, Admin can:

View how many posters and reels were completed per client.
See user-wise performance per client.
| Client  | Posters Completed | Reels Completed | Assigned Tasks       |
| ------- | ----------------- | --------------- | -------------------- |
| Client1 | 12                | 4               | 12 posters + 4 reels |
| Client2 | 9                 | 4               | 12 posters + 4 reels |
```
```
💾 DATA FLOW EXPLANATION
| Layer              | Technologies Used                                |
| ------------------ | ------------------------------------------------ |
| **Frontend**       | HTML5, CSS3, JavaScript                          |
| **Backend**        | Node.js, Express.js                              |
| **Database**       | MongoDB + Mongoose                               |
| **Other Packages** | bcryptjs, uuid, dotenv, axios, cors, body-parser |
| **Storage**        | MongoDB for persistent storage                   |

Frontend: Handles registration, schedule display, and task marking.
Backend: Manages authentication, schedule assignment, task updates, and monthly summary.
Database: Stores users, clients, weekly schedules, and task completion records.
```
```
🗂 Folder Structure
Schedule System/
│
├── backend/
│   ├── server.js
│   ├── .env
│   ├── package.json
│   ├── package-lock.json
│
├── frontend/
│   ├── index.html       # Login/Register
│   ├── admin.html       # Admin Panel
│   ├── user.html        # User Panel
└── README.md
```
```
🌐 Deployment
| Component | Platform      |
| --------- | ------------- |
| Frontend  | Netlify       |
| Backend   | Render        |
| Database  | MongoDB Atlas |
```
```
👨‍💻 DEVELOPER

Developed by: Santhosh Kumar S
Role: Full Stack Developer
Project Type: Task & Schedule Management System
```
```
🏁 SUMMARY

The Schedule System simplifies workflow management for design teams by:

✅ Assigning weekly tasks per client.
✅ Allowing designers to mark completion.
✅ Generating monthly summaries.
✅ Supporting multi-client handling per designer.

This system ensures organization, efficiency, and accurate tracking of all design tasks within a company.
```
```

