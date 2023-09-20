
# Moviely React Documentation

## Overview

Moviely is a React-based application that allows users to search for movies and manage their watched movie list. It leverages various components and custom hooks to provide a seamless movie browsing experience.

## Components

### 1. **App**

- The main component that orchestrates the entire application.
- Manages movie search, movie details, and the watched movie list.

### 2. **Loader**

- A simple loading indicator component displayed during API requests.

### 3. **ErrorMessage**

- Displays error messages when there are issues with API requests.

### 4. **NavBar**

- The navigation bar component that contains the logo and search input.

### 5. **Search**

- Manages the movie search input and allows focusing using the "Enter" key.
- Clears the search query when the "Enter" key is pressed.

### 6. **NumResults**

- Displays the number of search results found.

### 7. **Main**

- The main content area that contains the movie list and movie details.

### 8. **Box**

- A collapsible container used to organize components within the main content area.

### 9. **MovieList**

- Displays a list of movies based on the search results.

### 10. **Movie**

- Represents an individual movie item in the list.

### 11. **MovieDetails**

- Displays detailed information about a selected movie.
- Allows users to rate and add movies to their watched list.

### 12. **StarRating**

- A reusable star rating input component.
- Allows users to rate movies using stars.

### 13. **Star**

- Represents an individual star within the StarRating component.
- Can be filled or empty based on user interaction.

### 14. **WatchedSummary**

- Displays a summary of watched movies, including average IMDb ratings, user ratings, and runtime.

### 15. **WatchedMoviesList**

- Lists watched movies and provides an option to delete them.

### 16. **WatchedMovie**

- Represents an individual watched movie in the list.
- Displays IMDb ratings, user ratings, and runtime.

## Custom Hooks

### 1. **useKey**

- Listens for specific keyboard events and triggers actions.
- Used to handle keyboard interactions, such as focusing on input fields and triggering actions.

### 2. **useLocalStorageState**

- Manages state data in local storage.
- Allows for the synchronization of state with a specific key in local storage.

### 3. **useMovies**

- Facilitates movie data fetching from the OMDB API based on user search queries.
- Manages the state of movies, loading status, and potential errors associated with API requests.

## API Integration

- Moviely integrates with the OMDB API (Open Movie Database) to fetch movie data based on user queries.
- The API key used for authentication is stored in a constant variable named `KEY`.

## Dependencies

- The project relies on various external libraries and icons, including React, PropTypes, and Phosphor Icons.

---

This concludes the documentation for your Moviely React application. The provided components and custom hooks work together to create a user-friendly movie browsing and management experience. If you have any further questions or need additional documentation, please feel free to ask.
