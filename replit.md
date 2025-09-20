# Studio Virtual Click - Digital Marketing Website

## Overview

This is a React-based digital marketing agency website for Studio Virtual Click, a company offering web development and digital marketing services. The application is built as a full-stack web application with a React frontend, Express.js backend, and PostgreSQL database integration. The site serves as a company portfolio and contact platform, featuring modern UI components, responsive design, and multilingual support (Spanish).

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: React with TypeScript using Vite as the build tool
- **UI Library**: Radix UI components with shadcn/ui design system
- **Styling**: Tailwind CSS with custom CSS variables for theming
- **Routing**: Wouter for client-side routing
- **State Management**: TanStack Query for server state management
- **Forms**: React Hook Form with Zod validation
- **Icons**: Font Awesome for icons and visual elements

### Backend Architecture
- **Runtime**: Node.js with Express.js framework
- **Language**: TypeScript with ES modules
- **API Pattern**: RESTful API with `/api` prefix routing
- **Middleware**: Custom logging middleware for request tracking
- **Development**: Vite integration for hot module replacement in development
- **Error Handling**: Centralized error handling middleware

### Data Storage
- **Database**: PostgreSQL with Neon serverless database provider
- **ORM**: Drizzle ORM for type-safe database operations
- **Schema**: User management schema with username/password authentication
- **Migrations**: Drizzle Kit for database schema management
- **Fallback Storage**: In-memory storage implementation for development/testing

### UI/UX Design System
- **Design Language**: Modern, professional design with gradient hero sections
- **Component Library**: Comprehensive shadcn/ui component set including forms, dialogs, navigation, and data display components
- **Responsive Design**: Mobile-first approach with Tailwind CSS breakpoints
- **Typography**: Inter font family for consistent text rendering
- **Color Scheme**: Neutral-based color palette with blue primary colors
- **Dark Mode**: Built-in dark mode support with CSS custom properties

### Page Structure
- **Home Page**: Complete single-page application with sections for hero, services, portfolio, contact, and footer
- **Navigation**: Smooth scrolling navigation between page sections
- **Contact Integration**: WhatsApp floating button for direct customer communication
- **Portfolio Showcase**: Grid-based project showcase with category tags
- **Service Presentation**: Six main service categories with feature highlights

## External Dependencies

### Core Framework Dependencies
- **React Ecosystem**: React 18+ with React DOM, React Hook Form, and TanStack Query
- **Build Tools**: Vite with TypeScript support and custom Replit plugins
- **Routing**: Wouter for lightweight client-side routing

### UI and Styling
- **Component Library**: Radix UI primitives for accessible components
- **Styling Framework**: Tailwind CSS with PostCSS processing
- **Icons**: Font Awesome CDN for comprehensive icon library
- **Fonts**: Google Fonts (Inter) for typography

### Database and Backend
- **Database Provider**: Neon Database (PostgreSQL serverless)
- **ORM**: Drizzle ORM with Drizzle Kit for migrations
- **Validation**: Zod for runtime type validation and schema validation
- **Session Management**: Connect-pg-simple for PostgreSQL session storage

### Development and Utilities
- **Development Server**: Vite with custom Replit integration plugins
- **Date Handling**: date-fns for date manipulation and formatting
- **Utility Libraries**: clsx and class-variance-authority for conditional styling
- **Carousel**: Embla Carousel for image/content carousels

### Third-Party Integrations
- **WhatsApp Business**: Direct integration for customer communication
- **Image Hosting**: Unsplash for portfolio and service imagery
- **Social Media**: Prepared integration points for Facebook, Instagram, LinkedIn, and Twitter