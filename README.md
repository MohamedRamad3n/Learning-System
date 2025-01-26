e-learning-admin-dashboard/
│
├── public/
│   ├── index.html
│   └── assets/              # Static assets like images, fonts, etc.
│
├── src/
│   ├── features/            # Feature-based modules
│   │   ├── auth/            # Authentication feature
│   │   │   ├── components/  # Reusable components for auth
│   │   │   ├── hooks/       # Custom hooks for auth
│   │   │   ├── services/    # API services for auth
│   │   │   ├── slice/       # Redux slice for auth
│   │   │   └── Auth.tsx     # Main auth component
│   │   │
│   │   ├── courses/         # Courses feature
│   │   │   ├── components/  # Reusable components for courses
│   │   │   ├── hooks/       # Custom hooks for courses
│   │   │   ├── services/    # API services for courses
│   │   │   ├── slice/       # Redux slice for courses
│   │   │   └── Courses.tsx  # Main courses component
│   │   │
│   │   ├── users/           # Users feature
│   │   │   ├── components/  # Reusable components for users
│   │   │   ├── hooks/       # Custom hooks for users
│   │   │   ├── services/    # API services for users
│   │   │   ├── slice/       # Redux slice for users
│   │   │   └── Users.tsx    # Main users component
│   │   │
│   │   └── settings/        # Settings feature
│   │       ├── components/  # Reusable components for settings
│   │       ├── hooks/       # Custom hooks for settings
│   │       ├── services/    # API services for settings
│   │       ├── slice/       # Redux slice for settings
│   │       └── Settings.tsx # Main settings component
│   │
│   ├── app/                 # Redux store and root reducer
│   │   ├── store.ts         # Redux store configuration
│   │   └── rootReducer.ts   # Combined root reducer
│   │
│   ├── components/          # Global reusable components 
│   ├── layouts/             # Layout components 
│   ├── services/            # Global API services and utilities
│   ├── hooks/               # Global custom hooks
│   ├── utils/               # Global utility functions
│   ├── types/               # Global TypeScript types/interfaces
│   ├── App.tsx              # Main App component
│   ├── index.tsx            # Entry point
│   └── routes.tsx           # Routing configuration
