# Workout App 🏋️‍♂️

A React, Redux, and MUI-powered workout app that helps users select workouts based on their fitness level and available time. Designed with atomic design principles. (Currently building it.)

### First, I made a UX&UI design in Figma to better plan component structure and use cases.
https://www.figma.com/design/8qXaIiz96Uunxu7wd41yM8/Fitness-app?node-id=0-1&t=h7pnOXUkSihoyzVz-1


## 🚀 Features

### User Registration & Login:

  - Users can register by entering their name.
  - If they have registered before, they can select their name from a list.
  - Users choose their fitness level (Beginner, Intermediate, Advanced, Expert).
  - Fitness levels are color-coded:
        🟢 Beginner (Pastel Green)
        🟡 Intermediate (Pastel Yellow)
        🟠 Advanced (Pastel Orange)
        🔴 Expert (Pastel Red)

### Dashboard

  - Displays workouts filtered based on the user's fitness level.
  - Categories: Abs, Legs, Arms, Full Body.

### Workout Selection:

  - Users choose workout duration (10, 20, or 30 minutes).
  - A list of 8 exercises for the selected duration appears.
    
### Workout Plan & Timer:

  - Displays the exercise name and an animated illustration.
  - Each exercise lasts 30 seconds with a 10-second break in between.
  - A progress bar slider visualizes the workout completion.


## Tech Stack

### Frontend:
 - ⚛️ React (Functional Components + Hooks)
 - 🏪 Redux Toolkit (State Management)
 - 🎨 Material UI (MUI) (UI Components)
 - 🌍 React Router (Navigation)

### Project Architecture:
 - Atomic Design (Reusable components)
 - Redux Store for managing global state
 - React Router for multi-page navigation



## Getting Started
1) git clone https://github.com/your-username/workout-app.git
2) cd workout-app
3) npm install
4) npm start



