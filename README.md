# usePopcorn

usePopcorn is a React movie app for searching films, viewing details, rating what you watched, and keeping a personal watchlist in local storage.

## Features

- Search for movies through the OMDb API
- View movie details, including plot, cast, runtime, genre, and IMDb rating
- Rate a movie before adding it to your watched list
- Track watched movies with summary stats for average IMDb rating, user rating, and runtime
- Persist watched movies in local storage
- Use keyboard shortcuts like `Enter` to focus search and `Escape` to close the details panel

## Tech Stack

- React 18
- Create React App
- OMDb API
- Local storage for persistence

## Getting Started

### Prerequisites

- Node.js installed on your machine

### Install dependencies

```bash
npm install
```

### Run the app locally

```bash
npm start
```

The app will open in development mode at `http://localhost:3000`.

### Build for production

```bash
npm run build
```

## Available Scripts

- `npm start` - start the development server
- `npm test` - run the test runner
- `npm run build` - create an optimized production build
- `npm run eject` - eject from Create React App

## Project Structure

- `src/App.js` - main application logic and UI composition
- `src/StarRating.js` - reusable star rating component
- `src/useMovies.js` - fetches movie search results from OMDb
- `src/useLocalStorageState.js` - syncs state with local storage
- `src/useKey.js` - keyboard shortcut helper

## Notes

The app uses a hardcoded OMDb API key in the source code, matching the course project setup. If you want to reuse it in another project, replace that key with your own OMDb API key.
