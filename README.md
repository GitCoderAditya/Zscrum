# Zcrum

#A modern, full-stack Jira clone built with Next.js 14 and cutting-edge technologies. This project implements core **Jira** functionalities with a clean, responsive interface.

## Tech Stack

- **Frontend**: Next.js 14, React, Tailwind CSS, Shadcn UI
- **Backend**: Next.js API Routes, Prisma ORM
- **Database**: Neon (Postgres)
- **Authentication**: Clerk
- **Styling**: Tailwind CSS with custom components

## Features

- User authentication and authorization
- Project management and organization
- Task creation and management
- Drag-and-drop interface
- Modern, responsive UI

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file with the following variables:
   ```
   DATABASE_URL=
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
   ```
4. Initialize the database:
   ```bash
   npx prisma generate
   ```
5. Run the development server:
   ```bash
   npm run dev
   ```

Visit `http://localhost:3000` to see the application.
