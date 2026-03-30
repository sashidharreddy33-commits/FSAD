# Nexus Campus Event Portal

A full-stack campus event portal with auth, role-based dashboards, and event management.

## Quick Start (No install needed)
```bash
node start.js
```
Browser opens automatically at **http://localhost:3000/login.html**

## All Run Modes
| Command                      | What opens                                  |
|------------------------------|---------------------------------------------|
| `node start.js`              | Server + **Login page**                     |
| `node start.js --admin`      | Server + **Admin dashboard** directly       |
| `node start.js --port 8080`  | Custom port                                 |
| `npm start`                  | Same as `node start.js`                     |
| `npm run admin`              | Start + open admin                          |
| `npm run server`             | Express backend API only                    |

## Pages
- **login.html** — Entry point, Student/Admin role toggle
- **signup.html** — New student registration
- **user-dashboard.html** — Student: browse events, register, calendar, profile
- **admin-dashboard.html** — Admin: manage events, all registrations, students

## Demo Credentials
| Role    | Email                     | Password    |
|---------|---------------------------|-------------|
| Student | student@university.edu    | student123  |
| Admin   | admin@university.edu      | admin123    |
