# springProject
# Accounting of University Premises

This Java Spring project aims to develop a comprehensive system for managing and accounting for university premises, including classrooms, labs, offices, etc. The system provides functionalities for premises management, booking, reporting, notifications, maintenance tracking, search, access control, and calendar integration.

## Table of Contents
1. [Functional Requirements](#functional-requirements)
2. [Mockups](#mockups)
3. [System Behavior](#system-behavior)
4. [REST API Endpoints](#rest-api-endpoints)
5. [Installation and Setup](#installation-and-setup)
6. [Usage](#usage)
7. [Contributing](#contributing)
8. [License](#license)

## Functional Requirements

1. **User Authentication:** Users can register and log in with roles such as Admin, Faculty, and Staff.
2. **Dashboard:** Admins have access to a dashboard showing statistics and summaries of all premises.
3. **Premises Management:** Admins can add, edit, and delete premises with details like room number, capacity, etc.
4. **Booking System:** Faculty and Staff can book available premises for lectures, meetings, etc., with conflict resolution.
5. **Reporting:** Generate reports on premises usage, bookings, availability, etc., with filtering options.
6. **Notifications:** Automated notifications for booking confirmations, reminders, etc., based on user preferences.
7. **Maintenance Tracking:** Track maintenance activities for premises, including repairs and inspections.
8. **Search and Filter:** Users can search for premises by various criteria and apply filters.
9. **Access Control:** Role-based access control for different system functionalities.
10. **Calendar Integration:** Sync booking schedules with users' calendars for automatic updates and reminders.

## Mockups

Mockups for the user interface can be found in the ![ER-diagram](https://drawsql.app/teams/pnu-7/diagrams/kursova) directory.

## System Behavior

The system handles user authentication, authorization, data storage, business logic, and integration with external calendars. Users interact with the system through a web interface.

## REST API Endpoints

The following REST API endpoints are available:
- `/api/auth/login` - User login endpoint.
- `/api/auth/register` - User registration endpoint.
- `/api/premises` - CRUD operations for premises.
- `/api/bookings` - Booking management endpoints.
- `/api/reports` - Endpoint to generate reports.
- `/api/notifications` - Endpoint to send notifications.
- `/api/maintenance` - Maintenance tracking endpoints.
- `/api/search` - Endpoint for searching and filtering premises.
- `/api/users` - User management endpoints.
- `/api/calendar` - Endpoint for calendar integration.

## Installation and Setup


