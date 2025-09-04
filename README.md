# Streamverse

A modern, responsive video streaming platform built with React that provides an immersive video viewing experience with trending videos, personalized recommendations, and interactive features.

## Overview

Streamverse is a comprehensive video streaming application that combines the power of React with modern web technologies to deliver a seamless video viewing experience. The platform features a clean, intuitive interface designed for both desktop and mobile users.

## Features

- **Trending Videos**: Discover the most popular videos of the week
- **Continue Watching**: Resume where you left off with your video progress
- **Personalized Recommendations**: AI-powered video suggestions based on your preferences
- **Interactive Comments**: Engage with other viewers through comments
- **Notifications**: Stay updated with real-time notifications
- **User Profiles**: Manage your account and preferences
- **Video Search**: Find your favorite content quickly
- **Responsive Design**: Optimized for all devices and screen sizes

## Live Demo

Visit the live application: [Streamverse](https://BhaveshMukheja.github.io/Streamverse)

## Technology Stack

- **Frontend Framework**: React 18.2.0
- **Routing**: React Router DOM 6.9.0
- **Styling**: CSS3 with custom components
- **Icons**: Font Awesome 4.7.0
- **Testing**: Jest with React Testing Library
- **Deployment**: GitHub Pages
- **Build Tool**: Create React App

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/atis11/Streamverse
   cd Streamverse
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to view the application

## Project Structure

```
src/
├── Components/
│   ├── Homepage/           # Main landing page with video sections
│   ├── Login-Signup/       # Authentication components
│   ├── Modal/              # Reusable modal components
│   ├── Navbar/             # Navigation header
│   ├── NotifSection/       # Notification system
│   ├── Profile/            # User profile management
│   └── VideoStreaming/     # Video player and streaming features
├── App.js                  # Main application component
├── App.css                 # Global styles
└── index.js               # Application entry point
```

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run deploy` - Deploys to GitHub Pages
- `npm run eject` - Ejects from Create React App (one-way operation)

## Key Components

### Homepage
- **Trending Section**: Features the most popular video of the week
- **Continue Watching**: Horizontal scrollable list of videos in progress
- **Recommendations**: Personalized video suggestions in a grid layout

### Video Streaming
- **Video Player**: Embedded YouTube video player with custom controls
- **Comments System**: Interactive comment section for viewer engagement
- **Recommendations**: Related videos sidebar for extended viewing

### User Experience
- **Responsive Navigation**: Clean, intuitive navigation bar
- **Modal System**: Reusable modal components for notifications and comments
- **Profile Management**: User account and preference settings

## Design Features

- **Modern UI/UX**: Clean, intuitive interface design
- **Responsive Layout**: Mobile-first responsive design
- **Smooth Animations**: CSS transitions and hover effects
- **Consistent Theming**: Unified color scheme and typography

## Deployment

The application is automatically deployed to GitHub Pages using the `gh-pages` package. The deployment process includes:

1. Building the production version
2. Pushing to the `gh-pages` branch
3. Automatic deployment to GitHub Pages

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## Support

If you have any questions or need support, please open an issue in the GitHub repository or contact the development team.

---

**Developed by the Streamverse Team**