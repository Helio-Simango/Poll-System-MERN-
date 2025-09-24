# Poll System - MERN Stack Capstone Project

## 🔖 Project Title & Description

**Poll System** - A full-stack web application for creating, managing, and participating in polls. Users can create custom polls with multiple options, share them with others, and view real-time results. The system provides analytics on poll participation and results.

**Who it's for**: Anyone who needs to gather opinions, make group decisions, or conduct quick surveys. Perfect for teams, educators, event organizers, and community managers.

**Why it matters**: This project demonstrates mastery of the MERN stack while solving a real-world need for easy opinion gathering and decision-making tools.

## 🛠️ Tech Stack

### Frontend
- **React** - UI framework
- **React Router** - Client-side routing
- **Axios** - HTTP client for API calls
- **Tailwind CSS** - Styling and responsive design
- **Chart.js** - Data visualization for poll results
- **React Hook Form** - Form handling and validation

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **JWT** - Authentication tokens
- **bcryptjs** - Password hashing
- **CORS** - Cross-origin resource sharing

### Development Tools
- **VS Code** - Primary code editor
- **Postman** - API testing
- **MongoDB Compass** - Database management
- **Git & GitHub** - Version control

## 🧠 AI Integration Strategy

### Code Generation
I'll use **Cursor IDE** with AI agent mode to scaffold components and features:
- Generate React components with proper props typing
- Create Express.js route handlers and middleware
- Build MongoDB Mongoose models and schemas
- Develop API endpoints with proper error handling

**Sample Prompt**: "Create a React component for a poll creation form with fields for question, options (dynamic add/remove), expiration date, and privacy settings. Use React Hook Form for validation and Tailwind CSS for styling."

### Testing Support
Using **Jest** and **Supertest** with AI assistance:
- Generate unit tests for utility functions and components
- Create integration tests for API endpoints
- Mock database operations and API responses

**Sample Prompt**: "Generate Jest tests for the poll voting API endpoint. Test cases should include: valid vote, duplicate vote prevention, voting on expired poll, and invalid poll ID. Use Supertest for HTTP assertions."

### Documentation
AI will assist with:
- Writing comprehensive JSDoc comments for functions
- Generating API documentation with OpenAPI/Swagger
- Creating component documentation with Storybook-style examples
- Maintaining updated README files

### Context-Aware Techniques
I'll implement several AI workflow strategies:

**API Spec Integration**:
- Feed Mongoose schemas to AI to generate corresponding API endpoints
- Use OpenAPI specifications to create client-side API clients
- Generate CRUD operations based on database models

**File Tree Context**:
- Provide entire component file structures for consistent prop passing
- Share middleware chain configurations for proper authentication flow
- Maintain consistent error handling patterns across the application

**Diff-Based Generation**:
- Use git diffs to generate appropriate commit messages
- Analyze code changes to suggest improvements or identify potential issues
- Generate migration scripts for database schema updates

### In-Editor/PR Review Tooling

**Primary Tool**: **Cursor IDE**
- Real-time code suggestions and completions
- Code review and refactoring suggestions
- Error detection and debugging assistance
- Automated code formatting and linting

**PR Review Strategy**:
- Use AI to generate descriptive commit messages based on changes
- Automatically create PR descriptions summarizing features/fixes
- Identify potential bugs or security issues in code changes
- Suggest performance optimizations and best practices

## 📋 Project Features

### Core Functionality
- User authentication (register/login)
- Create polls with multiple options
- Vote on polls (anonymous or authenticated)
- Real-time results visualization
- Poll sharing via unique links
- Poll expiration settings

### Advanced Features
- Analytics dashboard for poll creators
- Duplicate vote prevention (IP-based)
- Responsive design for mobile devices
- Export poll results as CSV/PDF
- Poll categories and tags

## 🗂️ Project Structure

```
poll-system/
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/         # Page components
│   │   ├── services/      # API calls
│   │   └── utils/         # Helper functions
├── server/                # Express backend
│   ├── controllers/       # Route handlers
│   ├── models/           # Mongoose models
│   ├── routes/           # API routes
│   ├── middleware/       # Custom middleware
│   └── config/           # Database configuration
└── docs/                 # Documentation
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or Atlas)
- Git

### Installation
```bash
# Clone the repository
git clone <repository-url>
cd poll-system

# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install

# Start development servers
# Backend (runs on port 5000)
cd ../server
npm run dev

# Frontend (runs on port 3000)
cd ../client
npm start
```

## 🤖 AI Usage Examples

### Development Workflow
1. **Component Creation**: Use AI to generate boilerplate React components
2. **API Development**: Scaffold Express routes and controllers based on schema
3. **Testing**: Auto-generate test cases for new features
4. **Documentation**: Maintain updated docs with AI assistance

### Sample AI Prompts
```bash
# Generate authentication middleware
"Create JWT authentication middleware for Express.js that verifies tokens and protects routes"

# Create database models
"Design a Mongoose schema for Poll with fields: question, options array, creator, expiresAt, and votes"

# Build responsive UI
"Create a responsive poll results component using Chart.js with mobile-friendly labels"
```

## 📞 Support

For questions or issues regarding this project, please open an issue in the GitHub repository.

---

*This project plan was created with AI assistance as part of a capstone development exercise.*
