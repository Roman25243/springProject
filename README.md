# Облік приміщень університету (University Premises Accounting)

This project is a Java Spring application for managing university premises, including classrooms, labs, offices, and more. It features user authentication, premises management, booking systems, reporting, and maintenance tracking.

## Functional Requirements

1. **User Authentication**
   - Users can register and log in to the system.
   - Users have roles such as Admin, Faculty, and Staff.

2. **Dashboard**
   - Admins have access to a dashboard showing statistics and summaries of all premises.
   - Faculty and Staff have limited dashboard access.

3. **Premises Management**
   - Admins can add, edit, and delete premises.
   - Premises include classrooms, labs, offices, etc., with details like room number, capacity, equipment, etc.
   - Premises can be categorized by building, floor, and department.

4. **Booking System**
   - Faculty and Staff can book available premises for lectures, meetings, or other activities.
   - Booking includes date, time, purpose, and participants.
   - Conflict resolution for double bookings or overlapping schedules.

5. **Reporting**
   - Generate reports on premises usage, bookings, availability, and maintenance schedules.
   - Reports can be filtered by date, building, department, etc.

6. **Notifications**
   - Automated notifications for booking confirmations, reminders, and schedule changes.
   - Email or in-app notifications based on user preferences.

7. **Maintenance Tracking**
   - Track maintenance activities for each premise, including repairs, inspections, and upgrades.
   - Maintenance history and upcoming tasks are visible to admins.

8. **Search and Filter**
   - Users can search for premises by various criteria such as room number, building, capacity, etc.
   - Filter options for available premises, equipment availability, accessibility features, etc.

9. **Access Control**
   - Role-based access control for different system functionalities.
   - Admins can manage user roles and permissions.

10. **Integration with Calendar**
    - Sync booking schedules with users' calendars (e.g., Google Calendar, Outlook).
    - Automatic updates and reminders for booked events.

## Mockups
ER-diagram

## System Behavior and REST API Endpoints

### System Behavior

- Users interact with the system through a web interface.
- The system handles authentication, authorization, data storage, and business logic.
- Actions such as adding premises, booking, generating reports, etc., are processed by the system.

### REST API Endpoints

- **Authentication**
  - `POST /api/auth/login`: User login endpoint.
  - `POST /api/auth/register`: User registration endpoint.

- **Premises Management**
  - `GET /api/premises`: Retrieve a list of all premises.
  - `POST /api/premises`: Add a new premise.
  - `PUT /api/premises/{id}`: Update an existing premise.
  - `DELETE /api/premises/{id}`: Delete a premise.

- **Booking Management**
  - `GET /api/bookings`: Retrieve a list of all bookings.
  - `POST /api/bookings`: Create a new booking.
  - `PUT /api/bookings/{id}`: Update an existing booking.
  - `DELETE /api/bookings/{id}`: Delete a booking.

- **Reporting**
  - `GET /api/reports`: Generate reports.

- **Notifications**
  - `POST /api/notifications`: Send notifications.

- **Maintenance Tracking**
  - `GET /api/maintenance`: Retrieve maintenance records.
  - `POST /api/maintenance`: Add a new maintenance record.
  - `PUT /api/maintenance/{id}`: Update an existing maintenance record.
  - `DELETE /api/maintenance/{id}`: Delete a maintenance record.

- **Search and Filter**
  - `GET /api/search`: Search for premises.

- **User Management**
  - `GET /api/users`: Retrieve a list of all users.
  - `POST /api/users`: Add a new user.
  - `PUT /api/users/{id}`: Update an existing user.
  - `DELETE /api/users/{id}`: Delete a user.

- **Calendar Integration**
  - `POST /api/calendar`: Sync booking schedules with external calendars.

## Installation



