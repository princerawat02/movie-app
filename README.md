# Movie App

A React-based movie application that allows users to search for movies, view details, and explore trending movies. The app fetches data from the [TMDB API](https://www.themoviedb.org/documentation/api) and uses **Appwrite** to store and display the most searched queries in the trending section.

Check out the live demo: [Movie App](https://movie-app-chi-puce.vercel.app/)

## Features

- Search for movies by title.
- View trending movies based on most searched queries.
- Display movie details (title, plot, rating, and poster).
- Debounced search to minimize unnecessary API calls.
- Responsive and user-friendly interface.

## Technologies Used

- **React**: Front-end library for building the user interface.
- **Vite**: Build tool and development server.
- **TMDB API**: Provides movie data.
- **Appwrite**: Backend server for storing the most searched queries.
- **Tailwind CSS**: Utility-first CSS framework for styling the application.
- **React-Use**: Debounce hook to limit API requests.

## Installation

### Prerequisites

- [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed.

### Steps to Set Up Locally

1. Clone the repository:
    ```bash
    git clone https://github.com/princerawat02/movie-app.git
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Run the development server:
    ```bash
    npm run dev
    ```

    The app will be available at `http://localhost:3000`.

## Environment Variables

Create a `.env` file in the root directory and add the following:

```env
VITE_TMDB_API_KEY=your_tmdb_api_key
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
```
