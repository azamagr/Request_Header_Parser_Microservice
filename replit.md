# Request Header Parser Microservice

## Overview
This is a Request Header Parser Microservice built with Node.js and Express. It's a freeCodeCamp API project that parses HTTP request headers and returns information about the client.

**Current State**: Successfully imported and configured for Replit environment. The app is running on port 5000 and ready for development and deployment.

## Recent Changes
- **October 7, 2025**: Initial import and setup for Replit
  - Configured Express server to bind to 0.0.0.0:5000 for Replit compatibility
  - Installed all npm dependencies (cors, dotenv, express)
  - Configured workflow to run `npm start`
  - Set up deployment configuration for autoscale deployment

## Project Architecture

### Technology Stack
- **Runtime**: Node.js
- **Framework**: Express.js
- **Dependencies**:
  - `cors`: Enable CORS for remote API testing
  - `dotenv`: Environment variable management
  - `express`: Web application framework

### File Structure
```
.
├── index.js           # Main application file
├── package.json       # Node.js dependencies and scripts
├── public/           
│   └── style.css      # Stylesheet
├── views/
│   └── index.html     # Frontend HTML
├── sample.env         # Sample environment configuration
└── README.md          # Project documentation
```

### API Endpoints
- `GET /` - Serves the frontend HTML page
- `GET /api/hello` - Test endpoint returning a greeting
- `GET /api/whoami` - Main endpoint (to be implemented) that returns client header information

### Server Configuration
- **Development Port**: 5000
- **Host**: 0.0.0.0 (configured for Replit proxy compatibility)
- **Deployment**: Configured for autoscale deployment with `npm start`

## Development Notes
- The app uses Express to serve static files from the `public` directory
- CORS is enabled for cross-origin API testing
- Port configuration uses environment variable PORT with fallback to 5000
