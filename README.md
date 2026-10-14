# FitTrack Lite — Frontend

## 1. Project Overview

FitTrack Lite is a full-stack fitness and workout progress tracking platform. The frontend provides the user interface for authentication, workout management, fitness progress tracking, and dashboard visualization.

This repository contains the frontend application built using React and Vite.

## 2. Technologies Used

| Technology | Purpose |
|---|---|
| React.js | User interface |
| Vite | Development server and build tool |
| JavaScript | Application logic |
| HTML5 | Page structure |
| CSS3 | Styling |
| npm | Package management |
| Vercel | Frontend deployment |

## 3. Features

- User registration and login interface
- Fitness dashboard
- Workout plan management
- Workout history tracking
- Progress and body measurement tracking
- Personal records management
- Integration with backend REST APIs

## 4. Prerequisites

Install the following software:

| Tool | Version |
|---|---|
| Node.js | 18+ |
| npm | Included with Node.js |
| Web browser | Chrome, Edge, Firefox, etc. |

Check your installation:

```bash
node -v
npm -v
```

## 5. Run Locally in VS Code

### Step 1: Clone the repository

```bash
git clone https://github.com/mihirm262-hue/FitTrack-Lite-Frontend.git
cd FitTrack-Lite-Frontend
```

### Step 2: Install dependencies

```bash
npm install
```

### Step 3: Start the development server

```bash
npm run dev
```

Open the local URL displayed in the terminal, usually:

`http://localhost:5173`

## 6. Backend Integration

The frontend communicates with the FitTrack Lite backend through REST API endpoints.

**Backend repository:**

https://github.com/mihirm262-hue/FitTrack-Lite-Backend

During local development, the backend is expected to run at:

`http://localhost:8080`

The Vite proxy configuration should forward `/api` requests to the backend. Check `vite.config.js` to confirm the configuration.

## 7. Build for Production

Run:

```bash
npm run build
```

Vite generates the production build in the `dist` directory.

To test the production build locally:

```bash
npm run preview
```

## 8. Deployment Using Vercel

1. Sign in to Vercel.
2. Import the `FitTrack-Lite-Frontend` GitHub repository.
3. Select Vite as the framework if it is not detected automatically.
4. Set the build command to `npm run build`.
5. Set the output directory to `dist`.
6. Configure the backend URL in `vercel.json` or the appropriate environment configuration.
7. Deploy the application.

Ensure the backend URL is correct and the backend permits requests from the deployed frontend.

## 9. Related Repository

**Backend:** https://github.com/mihirm262-hue/FitTrack-Lite-Backend

## 10. Author

Mihir  
Department: Electronics and Communication Engineering (ECE)
