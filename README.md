vdc-portal

A modern, full-stack dashboard and user management portal built using React, CoreUI, Node.js, and MongoDB. Designed as a modular, extensible boilerplate project — ideal for developers looking to build media dashboards, admin portals, or SaaS interfaces.

✨ Features

✉ User authentication with JWT (login/register)

📈 Modern admin dashboard UI with CoreUI 5

📁 Role-based authorization (Admin vs. User)

🔒 Protected routes and session management

🔍 Searchable file queue interface

📅 Cron job monitoring panel

💌 Notification system with unread counts

✨ Fully responsive and mobile-ready

📦 Tech Stack

Frontend

React 18+

Vite

CoreUI

Axios

Redux Toolkit

Backend

Node.js + Express

MongoDB (with Mongoose)

JWT Auth

Winston Logging

Cron for background tasks

⚙️ Setup Instructions

1. Clone the repo
```
git clone https://github.com/your-org/vdc-portal.git
cd vdc-portal
```
2. Install dependencies

Backend:
```
cd server
npm install
```
Frontend:
```
cd ../client
npm install
```
3. Create a .env file

# server/.env
PORT=5000
MONGODB_URI=mongodb://localhost:27017/vdcDB
JWT_SECRET=your_super_secret

4. Seed the database
```
node seedDatabase.js
```
5. Run the app

Backend:
```
npm run dev
```
Frontend:
```
npm run dev
```
🚀 Use Cases

Admin or media dashboards

Transcription or file processing platforms

Internal tools with role-based access

Starter for full-stack SaaS products

🔗 Contributing

We welcome PRs, ideas, and issue reports! Please fork the repo and submit a pull request.

✉ License

MIT License.

📷 Screenshots

(Add images/gifs of login screen, dashboard, and queue tables)

🚨 Related Project

Looking for a full data dashboard stack with real-time and historical analytics (InfluxDB, etc.)?
Check out our main project: visual-data-core

