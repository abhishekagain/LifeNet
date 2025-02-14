# LifeNet - Organ Transfer Management Platform

## Presented by RustedCoders
### Developed by Abhishek & Team

## 🌟 Overview
A comprehensive web-based organ transfer management platform designed to optimize global healthcare coordination for organ donation and transplantation. LifeNet streamlines the organ donation process, making it more efficient and accessible.

## 🚀 Key Features
- Real-time organ tracking and matching system
- Multi-role authentication with enhanced security
- Interactive and responsive dashboards
- Emergency contact management
- System status monitoring
- Comprehensive support system
- Quick statistics dashboard

## 💻 Technologies Used

### Frontend
- React.js with TypeScript
- Tailwind CSS for styling
- ShadcnUI components
- React Query for data fetching
- Wouter for routing

### Backend
- Express.js server
- PostgreSQL database
- Drizzle ORM
- Authentication using Passport.js

### Development Tools
- Vite for frontend build
- TypeScript for type safety
- Zod for schema validation
- TanStack Query for data management

## 📋 Requirements

### System Requirements
- Node.js v20.x or higher
- PostgreSQL 15.x or higher
- npm or yarn package manager

### Environment Variables
```env
DATABASE_URL=postgresql://...
SESSION_SECRET=your_session_secret
NODE_ENV=development
PORT=5000
```

## 🛠️ Installation & Setup

1. Clone the repository

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
- Create a `.env` file in the root directory
- Add the required environment variables

4. Run database migrations
```bash
npm run db:push
```

5. Start the development server
```bash
npm run dev
```

## 🏗️ Project Structure
```
project/
├── client/                # Frontend React application
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── hooks/        # Custom React hooks
│   │   ├── lib/          # Utility functions
│   │   ├── pages/        # Page components
│   │   └── App.tsx       # Main application component
├── server/                # Backend Express server
│   ├── routes/           # API routes
│   ├── middleware/       # Custom middleware
│   ├── storage.ts        # Database interface
│   └── index.ts         # Server entry point
└── shared/               # Shared code between frontend and backend
    └── schema.ts        # Database schema and types
```

## 🔒 Security Features
- Password hashing using bcrypt
- Session-based authentication
- CSRF protection
- Input validation using Zod
- SQL injection prevention through Drizzle ORM

## 🎯 Future Enhancements
1. Enhanced organ tracking with GPS
2. Mobile application development
3. AI-powered organ matching
4. Blockchain integration
5. Cross-border organ sharing features

## 👥 Team
- **Abhishek**: Lead Developer
- **Team Members**: Development and Design Support

## 📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 💡 Support
For technical support or queries:
1. Check the documentation
2. Use the in-app support system
3. Contact the development team

---
© 2025 RustedCoders. All Rights Reserved.
