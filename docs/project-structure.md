# Project Structure

The `vdc-portal` project is organized into two main directories: `client` and `server`. Below is an overview of the project's structure:

```
vdc-portal/
├── client/             # Frontend application
│   ├── public/         # Static assets
│   └── src/            # Source files
│       ├── assets/     # Images, fonts, and other static resources
│       ├── components/ # Reusable React components
│       ├── features/   # Feature-specific modules
│       ├── hooks/      # Custom React hooks
│       ├── layouts/    # Layout components
│       ├── pages/      # Page components
│       ├── routes/     # Route definitions
│       ├── store/      # Redux store configuration
│       ├── utils/      # Utility functions
│       └── main.jsx    # Entry point for the React application
│
├── server/             # Backend application
│   ├── config/         # Configuration files (e.g., database, authentication)
│   ├── controllers/    # Route handlers and business logic
│   ├── models/         # Mongoose models
│   ├── routes/         # Express route definitions
│   ├── utils/          # Utility functions and middleware
│   └── server.js       # Entry point for the Express server
│
├── docs/               # Documentation files
│   └── project-structure.md # This file
│
├── .gitignore          # Git ignore file
├── LICENSE             # License file
└── README.md           # Project overview and setup instructions
```

## Client Directory

The `client` directory contains the frontend of the application, built with React and Vite. Key subdirectories include:

- **public/**: Holds static assets that are publicly accessible.
- **src/**: Contains the main source code for the React application.
  - **assets/**: Stores images, fonts, and other static resources.
  - **components/**: Reusable React components used throughout the application.
  - **features/**: Modules related to specific features or functionalities.
  - **hooks/**: Custom React hooks for shared logic.
  - **layouts/**: Components that define the layout structure of pages.
  - **pages/**: Components representing individual pages.
  - **routes/**: Definitions for routing within the application.
  - **store/**: Configuration and slices for Redux state management.
  - **utils/**: Utility functions and helpers.
  - **main.jsx**: The entry point for the React application.

## Server Directory

The `server` directory contains the backend of the application, built with Node.js and Express. Key subdirectories include:

- **config/**: Configuration files for database connections, authentication, etc.
- **controllers/**: Functions that handle requests and contain business logic.
- **models/**: Mongoose schemas and models for MongoDB collections.
- **routes/**: Express route definitions mapping URLs to controllers.
- **utils/**: Utility functions and middleware for tasks like logging and error handling.
- **server.js**: The main entry point for starting the Express server.

## Docs Directory

The `docs` directory contains documentation files related to the project, including this `project-structure.md` file.

## Root Files

- **.gitignore**: Specifies files and directories that should be ignored by Git.
- **LICENSE**: The project's license file.
- **README.md**: Provides an overview of the project, setup instructions, and other relevant information.

This structure aims to maintain a clear separation between the frontend and backend components, promoting modularity and ease of maintenance.
