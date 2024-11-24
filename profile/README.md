# PulseCRM

[PulseCRM](https://pulsecrm.com) is a modern, full-featured Customer Relationship Management system built with cutting-edge technologies. It provides a robust platform for managing customer relationships, tracking activities, and analyzing business metrics.

## 🚀 Features

- **Account Management**: Comprehensive account administration with role-based permissions
- **Activity Tracking**: Monitor and log customer interactions and business activities
- **Analytics Dashboard**: Visual metrics and reporting with interactive charts
- **API Integration**: Secure API endpoints with key management
- **File Management**: S3-powered document storage and management
- **User Permissions**: Granular access control system
- **Responsive UI**: Modern, responsive interface built with Tailwind CSS

## 💻 Tech Stack

- **Frontend**:
  - Next.js 14
  - TypeScript
  - Tailwind CSS
  - React Query
  - Chart.js & Recharts
  - Radix UI Components
  - Storybook for component development

- **Backend**:
  - Next.js API Routes
  - PostgreSQL with Drizzle ORM
  - SendGrid Integration
  - AWS S3 Integration

- **Infrastructure**:
  - Docker containerization
  - Terraform for infrastructure management
  - AWS Cloud infrastructure
  - Vercel deployment support

- **Testing & Quality**:
  - Vitest for unit testing
  - Thunder Client for API testing
  - ESLint & Prettier for code quality
  - TypeScript for type safety

## 🛠️ Development

### Prerequisites

- Node.js >= 20
- npm >= 10
- Docker (for local development)
- PostgreSQL

### Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up local PostgreSQL:
   ```bash
   npm run postgres:start
   ```

4. Run database migrations:
   ```bash
   npm run drizzle:push
   ```

5. Start the development server:
   ```bash
   npm run dev
   ```

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run storybook` - Launch Storybook component explorer
- `npm test` - Run tests
- `npm run docker:build` - Build Docker container
- `npm run docker:run` - Run Docker container

## 📚 Documentation

- API documentation is available through Swagger UI
- Component documentation available in Storybook
- Database schema managed through Drizzle ORM

## 🔒 Security

- Argon2 for password hashing
- JWT-based authentication
- Role-based access control
- API key authentication for external integrations

## 🌟 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## 📄 License

This project is private and proprietary software.
