# Soundscape: Discover. Discuss. Document.

## Overview

Soundscape is a web-based platform designed to explore urban soundscapes, cultural identity, and the emotional impact of sound. This project was my way of connecting with the city of New York, providing users with an interactive space to reflect on and engage with their sonic surroundings. The website is live at [Soundscape Deployment](https://soundscape.up.railway.app/).

## Technologies Used

This project is built using a combination of frontend and backend technologies:

### Frontend:

- **Bootstrap 5**: Used for styling, layout design, and responsive UI components.
- **HTML5**: Structure and content of the pages.
- **CSS3**: Custom styling and enhancements.
- **JavaScript**: Enhancing interactivity and form handling.
- **Handlebars.js (hbs)**: Server-side templating for dynamic content rendering.

### Backend:

- **Node.js & Express.js**: Handles server-side logic and API endpoints.
- **MongoDB & Mongoose**: Database for storing user reflections, goals, and community discussions.
- **Passport.js**: Authentication and session management.
- **Moment.js**: Date formatting utilities.
- **Bcrypt.js**: Secure password hashing.

### Deployment:

- **Railway.app**: Used for live hosting and deployment.
- **MongoDB Atlas**: Cloud database for persistent storage.

## Website Pages & Features

### Home (`/`)

- Introduction to the project with the tagline: _Discover. Discuss. Document._
- Dynamic rendering based on authentication status (Landing page for new users, dashboard for logged-in users).

### Articles (`/articles`)

- Curated articles on urban soundscapes, cultural identity, and the emotional impact of sound.

### Community (`/community`)

- A space for users to log reflections and discuss insights inspired by sounds.
- Supports sorting and searching posts.
- Users can comment on posts.

### Mood (`/mood`)

- An interactive feature offering tracks and soundscapes that align with users' emotions.

### Audio Log (`/audiolog`)

- A personal journal where users can document reflections inspired by soundscapes.
- Entries can be added, sorted, and deleted.

### Sound Map (`/soundmap`)

- An interactive map with clickable pins that allow users to explore and listen to different soundscapes across Manhattan.

### Authentication Pages

- **Signup (`/signup`)**: New users can create an account with password validation.
- **Signin (`/signin`)**: Existing users can log in securely using Passport.js authentication.
- **Logout (`/logout`)**: Ends the user session and redirects to the homepage.

## Deployment & Live Demo

The project is hosted on **Railway.app**, and the live version can be accessed at:
[https://soundscape.up.railway.app/](https://soundscape.up.railway.app/)
