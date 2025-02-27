## Overview🎬

Movie Finder is a React-based web app that uses Appwrite and TMDB API to search and display trending movies. Users can search for any movie by name, and the system tracks the search count. The most searched movies appear in the "Trending Movies" section.

![Screenshot 2025-02-27 142424](https://github.com/user-attachments/assets/a0c55537-8543-435a-a316-6b91ae36d7ac)

![Screenshot 2025-02-27 142451](https://github.com/user-attachments/assets/b1e9a135-0699-4fee-bc5d-a70190253593)



## Features ✨

 - Search Movies: Fetch movies from the TMDB API.

 - Trending Movies: Track the most searched movies in the Appwrite database.

 - Appwrite Integration: Store and update search counts in the database.

 - Responsive UI: A modern and fast frontend built with Tailwind CSS.

## Tech Stack 🛠️

 - Frontend: React, Tailwind CSS

 - Backend: Appwrite (Database & API calls)

 - API: TMDB API

## Installation & Setup 🚀

1. Clone the Repository:

   ```bash
    git clone https://github.com/Sarika2003/Movie-Finder.git
    cd movie-finder
    ```

2. Install Dependencies:

   ```bash
   npm install
   ```

3. Setup Environment Variables:
   
   ```bash
   VITE_APPWRITE_URL=your_appwrite_url
   VITE_APPWRITE_PROJECT_ID=your_project_id
   VITE_APPWRITE_DATABASE_ID=your_database_id
   VITE_APPWRITE_COLLECTION_ID=your_collection_id
   VITE_TMDB_API_KEY=your_tmdb_api_key
   ```

4. Run the Project:

   ```bash
   npm run dev
   ```

