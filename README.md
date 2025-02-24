# LMS-Edemy

## Overview

LMS-Edemy is a Learning Management System built with React and Vite. This application provides educational content delivery with a modern, responsive interface.

## Technologies Used

- **React 18**: A JavaScript library for building user interfaces
- **Vite**: Next generation frontend tooling for faster development
- **Tailwind CSS 4**: A utility-first CSS framework for rapid UI development
- **React Router DOM 7**: Declarative routing for React applications
- **Clerk**: Complete user management and authentication solution
- **Quill**: Powerful rich text editor
- **React YouTube**: YouTube player component for React
- **RC Progress**: Progress bar component for React

## Features

- User authentication and management via Clerk
- Rich text content editing with Quill
- Video content integration with YouTube
- Progress tracking for learning activities
- Responsive design with Tailwind CSS

## Development Setup

### Prerequisites

- Node.js (latest LTS version recommended)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd lms-edemy
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

### Available Scripts

- `npm run dev` - Starts the development server
- `npm run build` - Builds the app for production
- `npm run lint` - Runs ESLint to check code quality
- `npm run preview` - Locally previews the production build

## Project Structure

- `src/` - Contains the source code
- `public/` - Static assets
- `package.json` - Project dependencies and scripts
- `vite.config.js` - Vite configuration
- `tailwind.config.js` - Tailwind CSS configuration
- `eslint.config.js` - ESLint configuration

## Plugins

This template uses the following Vite plugins:
- `@vitejs/plugin-react` - Uses Babel for Fast Refresh
- `@tailwindcss/vite` - Integrates Tailwind CSS with Vite

## Dependencies

### Core
- react: ^18.3.1
- react-dom: ^18.3.1
- react-router-dom: ^7.1.5
- tailwindcss: ^4.0.3

### UI and Components
- quill: ^2.0.3
- rc-progress: ^4.0.0
- react-youtube: ^10.1.0

### Authentication
- @clerk/clerk-react: ^5.22.10

### Utilities
- humanize-duration: ^3.32.1
- uniquid: ^1.1.4

## License

[License information]

## Contributors

[Contributor information]
