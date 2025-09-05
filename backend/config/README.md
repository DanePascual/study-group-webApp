# Configuration

This directory will contain configuration files for the backend application.

## Planned Configuration Files

```
config/
├── database.js      # Database connection settings
├── auth.js          # Authentication configuration (JWT secrets, etc.)
├── upload.js        # File upload settings (size limits, allowed types)
├── email.js         # Email service configuration
└── server.js        # Server settings (port, CORS, etc.)
```

## Environment Variables

Consider using environment variables for:
- Database connection strings
- JWT secrets
- API keys for external services
- Email service credentials
- File storage configuration