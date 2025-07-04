# 📅 Meeting Manager

## ✨ Project Description
The **Meeting Manager** is a comprehensive web-based application that revolutionizes meeting management for organizations, especially client service departments. It replaces inefficient spreadsheet-based systems with a centralized platform for scheduling, tracking, and analyzing meetings. Developed using **Angular (with NG-ZORRO)** for the front end, **ASP.NET Core (C#)** for the back end, and **SQL Server** for data storage, it integrates **Quartz Scheduler** for automated real-time status updates.

## 🎓 Project Summary
- **Internship Period**: Dec 2024 to April 2025  
- **Organization**: ARGA Investment Management India Pvt. Ltd.  
- **Institution**: Coimbatore Institute of Technology  
- **Guide**: Dr. S. Sikappi  

## 🌐 Tech Stack
- **Frontend**: Angular 19 + NG-ZORRO Ant Design  
- **Backend**: ASP.NET Core (C#), Dapper ORM  
- **Database**: Microsoft SQL Server  
- **Scheduler**: Quartz.NET for automated job execution  
- **Security**: MFA (Multi-Factor Authentication), RBAC (Role-Based Access Control), AES-256 File Encryption  

## 🌟 Key Features
- ✅ Create & Edit Meetings (with recurrence, agenda, type, and location)  
- 🙋 Participant Management with Conflict Detection  
- 📆 Visual Calendar View (daily/weekly/monthly)  
- ⏱ Automated Meeting Status Update (Quartz Scheduler)  
- 📤 File Upload (5 files max, 10MB per file, configurable)  
- 🔔 In-app Notifications via WebSocket  
- 🌍 Reports & Analytics (by date, type, user, frequency)  
- 🔎 Advanced Search and Filter (by date range, participants, title, status)  

## ✨ Unique Implementations
- 🔊 **Quartz Scheduler**: Automatically changes status between `Scheduled`, `In Progress`, and `Completed` based on current time.  
- 🔐 **AES-256 Encryption**: Ensures secure file upload and download.  
- 📊 **Analytics Dashboard**: Displays meeting trends by type, topic, and user engagement.  
- ⚠️ **Conflict Checker**: Detects overlapping meetings by user or participant.  
- 🔑 **MFA + RBAC**: Enforces strict access control by role.  

## 📈 Sample Use Cases
1. **Create Meeting** – Input topic, recurrence, upload files, assign participants.  
2. **Edit Meeting** – Allowed before meeting start; triggers notifications.  
3. **Calendar View** – Meetings shown with color-coded statuses and hover conflict alerts.  
4. **View Meeting** – Role-based: participants see view-only; organizers can edit.  

## 🛠 System Design Overview
- **Architecture**: Multi-tier structure (Client → API → DB)  
- **Scheduling**: Quartz.NET executes background tasks  
- **Frontend**: Angular + NG-ZORRO  
- **Backend**: ASP.NET Core REST API + Dapper ORM  
- **Data**: Meetings, Recurrences, Files, Notifications, Participants stored in SQL Server  

## 💡 Future Enhancements
- 📧 Email Notifications via SMTP  
- 🤖 AI-powered Smart Scheduling  
- 🔁 Reschedule & Accept Invitations  
- 🔗 Calendar Sync (Google/Outlook)  
- 📋 Editable Calendar Lists with Role Filters  

## 🖥 Deployment & Usage
- **Frontend**: `localhost:4200` (Angular CLI)  
- **Backend**: `localhost:5001` (.NET Core API)  
- **Database**: SQL Server  
- **Authentication**: Session-based MFA and RBAC  

## 🏁 Project Outcome
- Boosted team collaboration and meeting visibility  
- Secure and automated tracking of meeting statuses  
- Comprehensive reporting and analytics for decision-making  
- Real-time UI updates with role-based actions  


