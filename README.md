# Chirrup - Full Stack Web Development Project

## Overview

**Chirrup** is a full-stack social media application developed during my second year of Software Engineering studies. This project demonstrates my proficiency in building complete web applications with a focus on API development and modern front-end engineering practices.

## Tech Stack

- **Frontend**: Vue.js with Vite bundler
- **Backend**: Node.js with Express
- **Database**: SQL
- **Authentication**: Header-based authorization

## Key Features

- **User Management**: Create accounts, user authentication, and profile management
- **Social Interactions**: Follow/unfollow users, build social connections
- **Post Creation & Management**: Create, read, update, and delete posts
- **Like System**: Engage with posts through likes
- **Search Functionality**: Discover users and content
- **Feed System**: Dynamic feeds showing user interactions

## Skills Demonstrated

### API Development
This project showcases my ability to design and implement RESTful APIs with:
- Multiple endpoints for users, posts, social connections, and feeds
- Proper HTTP methods (GET, POST, PUT, DELETE)
- Request/response handling and data validation
- Header-based authentication and authorization
- Direct SQL database operations with create, read, update, and delete functionality

### Front-End Development
The Vue.js frontend demonstrates:
- Component-based architecture with reusable Vue components
- Client-side routing for seamless navigation
- API service layer for clean separation of concerns
- Interactive user interface for posting, searching, and social features
- State management across multiple views and pages

## Project Structure

```
front_end/          - Vue.js frontend application
  src/
    views/          - Page components
    components/     - Reusable UI components
    services/       - API service layer
    router/         - Client-side routing

fsd_chirrup_server/ - Node.js backend server
  app/
    controllers/    - Request handlers
    models/         - Database models
    routes/         - API route definitions
    lib/            - Authentication utilities
  tests/            - Test suite
```

## Testing

The project includes comprehensive test coverage written by the course lecturer, with all tests passing successfully. The tests validate user creation, authentication, social features, search functionality, post operations, and feed generation.

## Development Experience

This project was an excellent opportunity to apply full-stack development principles in a real-world scenario, solidifying my understanding of how frontend and backend systems communicate and work together to create a functional application.
