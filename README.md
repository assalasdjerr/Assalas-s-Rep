# Assalas's Portfolio

A modern portfolio website built with Next.js, Redux, and Shadcn UI components. This portfolio showcases projects, testimonials, and provides user authentication features.

## Screenshots

Here are some screenshots of the website:

### Homepage

<img width="581" alt="image" src="https://github.com/user-attachments/assets/adef6398-cd10-44d4-a418-6103e562a41f" />

_Homepage with project highlights and introduction_

### Projects Page

<img width="511" alt="image" src="https://github.com/user-attachments/assets/52c07fd6-e7c2-46f4-b155-7382b7cafa4e" />

_Projects page showing the portfolio items_

### Project Detail

<img width="518" alt="image" src="https://github.com/user-attachments/assets/f4f30361-6b27-4536-9f51-97579f94831e" />

_Detailed view of a project with technologies and features_

### Testimonials

<img width="515" alt="image" src="https://github.com/user-attachments/assets/ec70749a-a112-4990-9cc1-64bb7425bcc6" />

_Testimonials from clients and colleagues_

## Features

- **Responsive Design**: Optimized for both mobile and desktop viewing
- **Project Showcase**: Display and filter projects with detailed view options
- **Testimonials Section**: View, add, and edit testimonials
- **User Authentication**: Secure login and registration system
- **State Management**: Using Redux with redux-persist for persistent state

## Tech Stack

- **Frontend Framework**: Next.js 15
- **UI Library**: React 19
- **State Management**: Redux Toolkit & Redux Persist
- **Styling**: Custom CSS
- **Authentication**: Custom authentication system

## Getting Started

### Prerequisites

- Node.js 18+
- npm, yarn, pnpm or bun

### Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd assalas-portfolio
```

2. Install dependencies:

```bash
npm install
# or
yarn
# or
pnpm install
# or
bun install
```

3. Start the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the site.

## Project Structure

- `/src/app`: Page components and routing
- `/src/components`: Reusable UI components
- `/src/redux`: Redux store, slices, and provider
- `/src/styles`: CSS stylesheets
- `/public`: Static assets

## Redux Setup

This project uses Redux for state management with redux-persist to maintain state between sessions:

- `authSlice`: Manages user authentication state
- `temoignagesSlice`: Manages testimonials data
- Redux data is persisted to localStorage

## Deployment

The application can be deployed on Vercel or any other platform that supports Next.js applications:

```bash
npm run build
npm run start
```
