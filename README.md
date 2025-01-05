# Upcoming Movies
A movie catalog Android application that fetches popular movies from the Movie Database (TMDb) API and displays them in a grid. The application allows users to view movie details, mark movies as favorites, and request new popular movies.

## Table of Contents
- [About](#about)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About
Upcoming Movies is a simple Android application that demonstrates how to fetch and display data from a remote API. The application uses the TMDb API to retrieve a list of popular movies and displays them in a grid. Users can view movie details, mark movies as favorites, and request new popular movies.

## Features
* Fetches popular movies from the TMDb API
* Displays movies in a grid
* Allows users to view movie details
* Allows users to mark movies as favorites
* Allows users to request new popular movies
* Handles network errors and displays error messages

## Technology Stack
### Backend
* TMDb API for fetching movie data
### Frontend
* Android SDK for building the mobile application
* Kotlin programming language for writing application code
* Gradle for building and managing dependencies
### Other Tools
* Retrofit for making HTTP requests to the TMDb API
* Gson for parsing JSON responses from the TMDb API
* Glide for loading and displaying images
* Room persistence library for storing favorite movies locally

## Prerequisites
* Android Studio or other compatible IDE
* Gradle 7.5 or later
* Android SDK 26 or later
* Kotlin 1.7 or later

## Installation
```bash
# Clone the repository
git clone https://github.com/bimapopo345/Binar_Tugas-8_And-2_Bima-Prawang-Saputra.git
cd UpcomingMovies

# Build the project
./gradlew build

# Install the application on a connected device or emulator
./gradlew installDebug
```

## Usage
1. Launch the application on a connected device or emulator.
2. The application will display a grid of popular movies.
3. Tap on a movie to view its details.
4. Tap the favorite button to mark a movie as a favorite.
5. Pull down to refresh the list of movies or request new popular movies.

## API Documentation
The TMDb API documentation can be found at [https://developers.themoviedb.org/3](https://developers.themoviedb.org/3).

## Deployment
The application can be deployed to the Google Play Store using the Android Studio build and deployment tools.

## Contributing
Contributions to the project are welcome. Please submit a pull request with your changes and a brief description of what you've added or fixed.

## License
The project is licensed under the Apache License 2.0.

## Contact
For questions or issues, please contact [bimapopo345](https://github.com/bimapopo345).
