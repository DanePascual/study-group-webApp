# Study Group Web Application

A collaborative platform for students to create study groups, share resources, and engage in discussions.

## Project Structure

The project has been organized into separate frontend and backend directories for better maintainability and scalability.

### Frontend (`/frontend`)

Contains all client-side code and assets:

- **`/frontend/pages/`** - HTML pages
  - `dashboard.html` - Main dashboard after login
  - `landing-page.html` - Landing page for new users
  - `login.html` - User login page
  - `sign-up.html` - User registration page
  - `profile.html` - User profile management
  - `study-rooms.html` - Study rooms overview
  - `study-room-inside.html` - Individual study room interface
  - `resources.html` - File sharing and resource management
  - `discussion.html` - Discussion forum
  - `post.html` - Individual forum post view
  - `topic.html` - Forum topic view
  - `report.html` - Analytics and reporting
  - `reset-password.html` - Password reset functionality

- **`/frontend/assets/`** - Static assets
  - `signup-bg-image.png` - Background image for authentication pages

### Backend (`/backend`)

Prepared structure for future server-side implementation:

- **`/backend/api/`** - API endpoints and routes
- **`/backend/models/`** - Data models and database schemas
- **`/backend/config/`** - Configuration files
- **`/backend/utils/`** - Utility functions and helpers

## Getting Started

1. Open any HTML file in the `/frontend/pages/` directory in a web browser
2. Start with `landing-page.html` for the main entry point
3. Use `login.html` to access the authenticated sections of the application

## Features

- **Study Rooms** - Create and join virtual study groups
- **Resource Sharing** - Upload and share study materials
- **Discussion Forum** - Engage in academic discussions
- **User Profiles** - Manage personal information and academic details
- **Dashboard** - Overview of activities and study groups
- **Dark Mode** - Toggle between light and dark themes

## Current Implementation

The application currently runs entirely in the browser using:
- HTML5 with embedded CSS and JavaScript
- Bootstrap 5.3.0 for UI components
- Bootstrap Icons for iconography
- LocalStorage for data persistence

## Future Enhancements

The backend structure is prepared for future implementation of:
- User authentication and authorization
- Database integration
- Real-time chat and collaboration features
- File upload and storage
- Email notifications
- API endpoints for mobile app integration

## Navigation

All HTML files are located in `/frontend/pages/` and maintain their original navigation structure. The application uses relative paths for page navigation within the pages directory.