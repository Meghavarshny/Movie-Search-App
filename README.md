# CineSearch - Movie Search Application

A full-featured React movie search application that integrates with the OMDb API to provide comprehensive movie, TV show, and episode discovery.

🚀 Live Demo
Frontend Deployment
🔗https://moviesebuddy.netlify.app/

## 🎬 Features

- **Advanced Search**: Search for movies, TV shows, and episodes by title, keywords, or actors
- **Smart Filtering**: Filter results by content type (movies, series, episodes) using API endpoints
- **Detailed Views**: Rich movie details including plot, ratings, cast, crew, and awards
- **Responsive Pagination**: Navigate through large result sets efficiently
- **Beautiful UI**: Cinema-themed dark design with smooth animations
- **Error Handling**: Robust error handling with user-friendly messages
- **URL Navigation**: Shareable URLs with search parameters
- **Image Optimization**: Fallback images for missing posters

## 🚀 Technology Stack

- **Frontend Framework**: ReactJS with TypeScript
- **Styling**: Tailwind CSS with custom design system
- **Routing**: React Router for navigation
- **API Integration**: OMDb API for movie data
- **UI Components**: Shadcn/ui component library
- **Icons**: Lucide React icons

## 📱 Pages & Components

### Main Pages
- **Search Page** (`/`): Main search interface with grid results
- **Movie Details** (`/movie/:id`): Detailed movie information page

### Key Components
- **SearchBar**: Search input with type filtering and suggestions
- **MovieGrid**: Responsive grid layout for search results
- **MovieCard**: Individual movie cards with hover effects
- **Pagination**: Smart pagination with ellipsis for large result sets



## 📋 Project Structure

```
src/
├── components/           # Reusable UI components
│   ├── ui/              # Shadcn/ui components
│   ├── SearchBar.tsx    # Search interface
│   ├── MovieGrid.tsx    # Results grid
│   ├── MovieCard.tsx    # Individual movie cards
│   └── Pagination.tsx   # Pagination controls
├── pages/               # Main application pages
│   ├── SearchPage.tsx   # Main search page
│   ├── MovieDetails.tsx # Movie details page
│   └── NotFound.tsx     # 404 error page
├── services/            # API integration
│   └── omdbApi.ts       # OMDb API service
├── hooks/               # Custom React hooks
└── lib/                 # Utility functions
```
