# Movieist

Movieist is a web application for browsing movies and posting reviews. It features a React-based frontend and a Spring Boot-powered backend.

## Table of Contents

- [Movieist](#movieist)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Tech Stack](#tech-stack)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Running the Application](#running-the-application)
  - [Project Structure](#project-structure)
    - [Backend](#backend)
    - [Frontend](#frontend)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)
  - [Contact](#contact)

## Features

- Browse a list of movies
- View detailed information about each movie
- Post and view reviews for movies
- Responsive design

## Tech Stack

- **Backend**: Java, Spring Boot, Maven
- **Frontend**: React, Axios
- **Build Tools**: Maven, npm

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- Java 17 or higher
- Node.js 14.x or higher
- Maven 3.6.3 or higher

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/movieist.git
   cd movieist
   ```

### Running the Application

#### Backend

1. Navigate to the backend directory:

   ```bash
   cd Movieist/backend
   ```

2. Build and run the backend application:

   ```bash
   ./mvnw spring-boot:run
   ```

   This will start the backend server on `http://localhost:8080`.

#### Frontend

1. Open a new terminal and navigate to the frontend directory:

   ```bash
   cd Movieist/frontend
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Start the frontend application:

   ```bash
   npm start
   ```

   This will start the frontend development server on `http://localhost:3000`.

## Project Structure

### Backend

- **Main Application**: `src/main/java/dev/farhan/movieist/MovieistApplication.java`
- **Controllers**: Handles HTTP requests.
  - `MovieController.java`
  - `ReviewController.java`
- **Services**: Contains business logic.
  - `MovieService.java`
  - `ReviewService.java`
- **Repositories**: Interfaces for data access.
  - `MovieRepository.java`
  - `ReviewRepository.java`
- **Models**: Defines the data structure.
  - `Movie.java`
  - `Review.java`
- **Resources**: Configuration files.
  - `application.properties`
  - `.env.example`
- **Test**: Test cases.
  - `MovieistApplicationTests.java`

### Frontend

- **Main Application**: `src/index.js`, `src/App.js`
- **Components**: UI components.
  - `components/header/Header.js`
  - `components/hero/Hero.js`
  - `components/home/Home.js`
  - `components/reviewForm/ReviewForm.js`
  - `components/reviews/Reviews.js`
  - `components/trailer/Trailer.js`
- **API Config**: Axios configuration.
  - `src/api/axiosConfig.js`
- **Styling**: CSS files for styling components.
  - `src/App.css`
  - `src/index.css`
  - `components/hero/Hero.css`
  - `components/trailer/Trailer.css`

## Usage

- **Browse Movies**: Visit the homepage to see a list of movies.
- **View Movie Details**: Click on a movie to see more details.
- **Post Reviews**: Submit your review for a movie.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

---
