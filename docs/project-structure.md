# 📁 Project Structure

This document describes the folder structure of the `vdc-portal` project. The structure is designed to be modular and scalable for modern frontend and backend development.

```
src/
│
├── app/              # Application layer: routes, main App component, providers, routing
│   ├── routes/       # Application routes (or pages)
│   ├── app.tsx       # Main application component
│   ├── provider.tsx  # Global providers wrapper
│   └── router.tsx    # App router
│
├── assets/           # Static assets like images, fonts, icons, etc.
│
├── components/       # Reusable shared UI components
│
├── config/           # Global configurations and environment settings
│
├── features/         # Feature-based modules
│
├── hooks/            # Reusable hooks shared across the application
│
├── lib/              # Shared libraries or API integrations
│
├── stores/           # Global state management (e.g., Redux Toolkit slices)
│
├── testing/          # Test utilities, mocks, and setup files
│
├── types/            # Global TypeScript types and interfaces
│
└── utils/            # Utility functions
```
