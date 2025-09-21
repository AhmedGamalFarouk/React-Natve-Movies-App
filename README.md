# Movies App

A React Native application for browsing movies, viewing details, and managing favorites.


## Screens
<img src="https://github.com/user-attachments/assets/f3d4f35d-b866-4e91-baac-c738a58d895d" width="300" height="600" alt="Screenshot 1"/>
<img src="https://github.com/user-attachments/assets/a929730e-2b00-4fe5-9868-2d42081f98e6" width="300" height="600" alt="Screenshot 2"/>
<img src="https://github.com/user-attachments/assets/a90ccc1d-bf32-484d-b821-5510f1c826aa" width="300" height="600" alt="Screenshot 3"/>
<img src="https://github.com/user-attachments/assets/d00c1a48-467d-4b00-ac95-d6bcd133784e" width="300" height="600" alt="Screenshot 4"/>
<img src="https://github.com/user-attachments/assets/17a9e6af-817f-4d06-adf1-3df7d56c5538" width="300" height="600" alt="Screenshot 5"/>
<img src="https://github.com/user-attachments/assets/ffb0f01f-af23-429b-bf29-b823f60c6395" width="300" height="600" alt="Screenshot 6"/>
<img src="https://github.com/user-attachments/assets/51060cf1-d375-4241-a4c2-b7b3784a0fe2" width="300" height="600" alt="Screenshot 7"/>
<img src="https://github.com/user-attachments/assets/a3f42178-8782-492f-90a5-5638e4b79958" width="300" height="600" alt="Screenshot 8"/>


## Features

*   **Browse Movies:** Discover popular and trending movies.
*   **Movie Details:** View comprehensive information about each movie, including synopsis, cast, and ratings.
*   **Search Functionality:** Easily find movies by title.
*   **Favorites Management:** Add and remove movies from your personal favorites list.
*   **User Authentication:** Secure sign-up and sign-in processes.
*   **Category Filtering:** Filter movies by various categories.

## Installation

To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/movies-app.git
    cd movies-app
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Set up API Key:**
    This app uses The Movie Database (TMDb) API. You'll need to obtain an API key from [TMDb](https://www.themoviedb.org/documentation/api).
    Create a file named `.env` in the root of your project and add your API key:
    ```
    EXPO_PUBLIC_TMDB_API_KEY=YOUR_API_KEY
    ```

4.  **Run the application:**
    ```bash
    npm start
    # or
    yarn start
    ```
    This will open Expo Dev Tools in your browser. You can then run the app on an Android emulator, iOS simulator, or your physical device using the Expo Go app.

## Usage

*   **Welcome Screen:** New users can sign up, and existing users can sign in.
*   **Home Screen:** Browse a curated list of movies.
*   **Categories Screen:** Explore movies by different genres.
*   **Favorites Screen:** View and manage your saved movies.
*   **Movie Details Screen:** Tap on any movie to see its detailed information.
*   **Search Bar:** Use the search bar to find specific movies.

## API

This application utilizes [The Movie Database (TMDb) API](https://www.themoviedb.org/documentation/api) for movie data.

## Technologies Used

*   React Native
*   Expo
*   React Navigation
*   Axios (for API requests)
*   Tailwind CSS (or similar for styling, based on project structure)
*   AsyncStorage (for local data persistence, e.g., favorites)

## Project Structure

```
.
├── assets/                     # Static assets like images and icons
├── src/
│   ├── api/                    # API service integrations (e.g., movieDb.js)
│   ├── components/             # Reusable UI components
│   ├── navigation/             # Navigation stack and tab navigators
│   └── screens/                # Main application screens
├── App.js                      # Main application entry point
├── app.json                    # Expo configuration file
├── package.json                # Project dependencies and scripts
└── README.md                   # Project documentation (this file)
```

## License

This project is licensed under the MIT License. See the [`LICENSE`](./LICENSE) file for details.
