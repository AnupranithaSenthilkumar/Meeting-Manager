# Meeting Manager

## Project Description
The Meeting Manager is a comprehensive web-based application that revolutionizes meeting management for organizations, especially client service departments. It replaces inefficient spreadsheet-based systems with a centralized platform for scheduling, tracking, and analyzing meetings. Developed using Angular (with NG-ZORRO) for the front end, ASP.NET Core (C#) for the back end, and SQL Server for data storage, it integrates Quartz Scheduler for automated real-time status updates.


## Tech Stack
- Frontend: Angular 19 + NG-ZORRO Ant Design  
- Backend: ASP.NET Core (C#), Dapper ORM  
- Database: Microsoft SQL Server  
- Scheduler: Quartz.NET for automated job execution  
- Security: Multi-Factor Authentication (MFA), Role-Based Access Control (RBAC), AES-256 File Encryption  

## Key Features
- Create and edit meetings (with recurrence, agenda, type, and location)  
- Participant management with conflict detection  
- Visual calendar view (daily, weekly, monthly)  
- Automated meeting status updates via Quartz Scheduler  
- File upload (up to 5 files per meeting, 10MB each - configurable)  
- Real-time in-app notifications via WebSocket  
- Reports and analytics (by date, type, user, frequency)  
- Advanced search and filtering (by date range, participants, title, and status)  

## Unique Implementations
- Quartz Scheduler automatically updates statuses such as Scheduled, In Progress, and Completed  
- AES-256 encryption ensures secure file storage and transmission  
- Analytics dashboard displays meeting trends by type, topic, and user activity  
- Conflict detection prevents overlapping meetings for users  
- Role-based access ensures only authorized users can create or edit meetings  

## Sample Use Cases
1. Create Meeting – Input topic, recurrence, upload files, assign participants  
2. Edit Meeting – Allowed only before meeting starts; participants are notified  
3. Calendar View – Displays meetings with color-coded statuses and conflict indicators  
4. View Meeting – Role-based: participants view only; organizers and admins can edit  

## System Design Overview
- Architecture: Multi-tiered (Frontend → API → Database)  
- Scheduling: Background status automation using Quartz.NET  
- Frontend: Angular 19 with NG-ZORRO components  
- Backend: ASP.NET Core REST API with Dapper ORM  
- Data: Meetings, recurrence rules, files, notifications, and participants stored in SQL Server  

## Future Enhancements
- Email notifications for invitations and updates  
- AI-based smart meeting scheduling recommendations  
- Acceptance and rescheduling workflows for participants  
- Integration with external calendars like Outlook and Google  
- Editable calendar view with daily meeting list  

## Deployment and Usage
- Frontend served at: http://localhost:4200  
- Backend hosted at: https://localhost:5001  
- SQL Server configured locally or on a cloud instance  
- Authentication handled via session storage and MFA  

## Project Outcome
- Enhanced collaboration and scheduling transparency  
- Secure file handling and controlled access  
- Real-time tracking of meeting status  
- Exportable reports for performance and decision-making  


