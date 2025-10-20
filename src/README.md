# Mergington High School Activities

A comprehensive web application built with FastAPI and MongoDB that enables teachers to manage student enrollment in extracurricular activities at Mergington High School.

## Features

### Activity Management
- View all available extracurricular activities with detailed information
- Filter activities by category (Sports, Arts, Academic, Community, Technology)
- Filter activities by day of the week (Monday through Sunday)
- Filter activities by time range (Before School, After School, Weekend)
- Search activities by name, description, or schedule
- Real-time capacity tracking showing enrollment status and available spots

### Teacher Authentication
- Secure teacher login system with password hashing
- Session management with persistent authentication
- Role-based access (teachers and administrators)

### Student Registration Management
- Register students for activities (teachers only)
- Unregister students from activities (teachers only)
- Email-based student identification
- Automatic validation to prevent duplicate enrollments
- Capacity management to prevent over-enrollment

### User Interface
- Responsive design with modern styling
- Interactive activity cards with visual capacity indicators
- Real-time updates without page refresh
- Loading skeletons for better user experience
- Modal dialogs for authentication and registration

## Technology Stack

- **Backend**: FastAPI (Python web framework)
- **Database**: MongoDB with PyMongo driver
- **Authentication**: Argon2 password hashing for secure storage
- **Frontend**: Vanilla JavaScript with modern DOM APIs
- **Styling**: Custom CSS with responsive design

## Development Guide

For detailed setup and development instructions, please refer to our [Development Guide](../docs/how-to-develop.md).
