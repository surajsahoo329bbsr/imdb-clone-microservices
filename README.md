# IMDb Clone - Spring Boot Microservices API Documentation

## 1. Introduction
### 1.1 Purpose
This document provides a comprehensive guide to the API endpoints of our scalable microservices-based architecture. It details authentication mechanisms, request and response formats, API structures, and module-specific functionalities.

### 1.2 Modules & Tables
| Module                  | Tables                        |
|-------------------------|------------------------------|
| **Movie Module**        | movie, movie_cast, movie_genre |
| **TV Show Module**      | tv_show, tv_show_cast, tv_show_genre, tv_show_seasons, tv_show_episodes |
| **User Module**         | user, review, person |
| **Admin Module**        | admin, genre |
| **User Engagement Module** | watchlist, watch_history, favorite_list |

## 2. Authentication & Security
- Uses JWT-based authentication.
- **Role-based access control:**
  - **Admin:** Full access to create, modify, and delete resources.
  - **User:** Read access and the ability to post reviews, manage watchlists, and mark favorites.
- API security will be handled with Spring Security.

## 3. API Endpoints

For a detailed list of API endpoints, including request/response formats and access levels, refer to the full documentation:

📄 API Reference Document: IMDb Clone API Endpoints

This document contains comprehensive details on endpoints for movies, TV shows, user reviews, watchlists, favorites, and administrative actions.

## 4. Modules and Clubbed Tables

### 4.1 Movie Module

Tables: movie, movie_cast, movie_genre

Handles CRUD operations for movies and their cast/genre details.

### 4.2 TV Show Module

Tables: tv_show, tv_show_cast, tv_show_genre, tv_show_season, tv_show_episode

Manages TV show entries, including seasons, episodes, and cast information.

### 4.3 User Module

Tables: user, review, person, watchlist, favorite_list, watch_history

Supports user management, reviews, and engagement features like watchlists and favorites.

### 4.4 Admin Module

Tables: admin, genre, milestone

Provides administrative capabilities for managing content, genres, and system milestones.

### 4.5 User Engagement Module

Tables: watchlist, watch_history, favorite_list

Enables tracking of user interactions with movies and TV shows.

## 5. Conclusion
This document serves as a guideline for backend developers working on the API endpoints. Future modifications should follow the outlined principles for consistency and maintainability.

