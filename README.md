# Socially - A Twitter Clone

Socially is a Twitter clone built with modern web technologies including TypeScript, React, Next.js, Prisma, and PostgreSQL. This project aims to replicate the core features of Twitter, providing a platform for users to post updates, follow other users, and interact with content.

## Features

- **User Authentication**: Secure user authentication using Clerk.
- **Post Creation**: Users can create and share posts with text and images.
- **Follow System**: Follow and unfollow other users to see their posts in your feed.
- **Notifications**: Receive notifications for interactions such as likes and comments.
- **Responsive Design**: Fully responsive design for a seamless experience on both desktop and mobile devices.
- **Dark Mode**: Toggle between light and dark themes.

## Tech Stack

- **TypeScript**: Strongly typed programming language that builds on JavaScript.
- **React**: A JavaScript library for building user interfaces.
- **Next.js**: A React framework for server-side rendering and generating static websites.
- **Prisma**: An ORM for Node.js and TypeScript.
- **PostgreSQL**: A powerful, open-source object-relational database system.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- PostgreSQL database

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/socially.git
   cd socially
   ```

2. Install dependencies:

```sh
npm install
```

3. Set up environment variables:
   Create a

```sh
 .env
```

file in the root directory and add your PostgreSQL connection string and other necessary environment variables.

4. Run database migrations:

```sh
npx prisma migrate dev
```

5. Start the development server:

```sh
npm run dev
```

Feel free to customize this README file further to suit your project's specific details and requirements.
