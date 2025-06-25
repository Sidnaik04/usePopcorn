# 🍿 usePopcorn

A sleek and intuitive React-based movie discovery and tracking application that helps you explore, rate, and manage your movie watchlist.

## 🌟 Features

- **🔍 Movie Search**: Search for any movie using the OMDB API
- **⭐ Rating System**: Rate movies with an interactive star rating component
- **📝 Watchlist Management**: Add movies to your personal watched list
- **📊 Statistics Dashboard**: View your watching statistics including:
  - Total movies watched
  - Average IMDb rating
  - Average user rating
  - Total runtime
- **🎬 Detailed Movie Information**: View comprehensive movie details including:
  - Plot summary
  - Cast and director information
  - Release date and runtime
  - Genre and IMDb rating
- **💾 Persistent Storage**: Your watchlist persists using local storage
- **⌨️ Keyboard Shortcuts**: 
  - Press `Enter` to focus search bar
  - Press `Escape` to close movie details

## 🚀 Live Demo

**[View Live Application](https://use-popcorn-b51m.vercel.app/)**

## 📸 Screenshots

### Movie Search & Results
<div align="center">
  
<img src="https://github.com/user-attachments/assets/04d8d3d7-fad3-4a56-a84c-db12d73f42cc" alt="Movie search interface showing Interstellar search results with detailed movie information" width="800">

*Search for movies and view detailed information including ratings, plot, cast, and director*

### App Features

  
**Interactive Rating System & Movie Details**

<img src="https://github.com/user-attachments/assets/fb55df5d-25a2-4c85-a023-11d89a14a33e" alt="One Piece movie details with 10-star rating system" width="30%"> <img src="https://github.com/user-attachments/assets/381ec0c4-23eb-436b-a6bc-eb5079e94b6d" alt="Your Name movie details showing plot and cast information" width="30%">

*Rate movies using the interactive star rating system and view comprehensive movie information*

**Search Results & Personal Watchlist**

<img src="https://github.com/user-attachments/assets/92a4f129-ff44-4029-bde4-d816da1c8239" alt="Search results showing multiple movies with Your Name titles" width="30%"> <img src="https://github.com/user-attachments/assets/298de758-b84d-4273-aef2-15065ad51aaf" alt="Personal watchlist showing watched movies with statistics dashboard" width="30%">

*Browse search results and track your watched movies with personal ratings and statistics*

</div>

## 🛠️ Tech Stack

- **Frontend**: React.js
- **Styling**: CSS3
- **API**: OMDB API (Open Movie Database)
- **Deployment**: Vercel
- **Storage**: Browser Local Storage

## 🏗️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/usepopcorn.git
   cd usepopcorn
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory:
   ```env
   REACT_APP_OMDB_KEY=your_omdb_api_key_here
   ```
   
   Get your free API key from [OMDB API](http://www.omdbapi.com/apikey.aspx)

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Open your browser**
   Navigate to `http://localhost:3000`

## 🔧 Build for Production

```bash
npm run build
```

## 📁 Project Structure

```
usepopcorn/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── App.js
│   │   ├── StarRating.js
│   │   └── ...
│   ├── hooks/
│   │   ├── useMovies.js
│   │   ├── useLocalStorageState.js
│   │   └── useKey.js
│   ├── index.css
│   └── index.js
├── .env
├── package.json
└── README.md
```

## 🎯 Key Components

- **App**: Main application component managing state and layout
- **StarRating**: Reusable star rating component
- **MovieList**: Displays search results
- **MovieDetails**: Shows detailed information about selected movies
- **WatchedSummary**: Statistics dashboard for watched movies

## 🔗 Custom Hooks

- **useMovies**: Handles movie fetching and search functionality
- **useLocalStorageState**: Manages persistent state with localStorage
- **useKey**: Handles keyboard event listeners

## 🌐 API Integration

This application uses the [OMDB API](http://www.omdbapi.com/) to fetch movie data including:
- Movie search results
- Detailed movie information
- Poster images
- Ratings and metadata

## 🚀 Deployment

The application is deployed on Vercel with the following configuration:

1. **Environment Variables**: Set `REACT_APP_OMDB_KEY` in Vercel dashboard
2. **Build Settings**: 
   - Framework: Create React App
   - Build Command: `npm run build`
   - Output Directory: `build`

## 📝 Usage

1. **Search Movies**: Type in the search bar to find movies
2. **View Details**: Click on any movie to see detailed information
3. **Rate Movies**: Use the star rating system to rate movies
4. **Add to Watchlist**: Click "Add to list" to save movies to your watchlist
5. **Manage Watchlist**: View your statistics and remove movies from your list

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [OMDB API](http://www.omdbapi.com/) for providing movie data
- [React](https://reactjs.org/) for the amazing framework
- [Vercel](https://vercel.com/) for seamless deployment

## 📧 Contact

Your Name - [@yourusername](https://twitter.com/yourusername) - your.email@example.com

Project Link: [https://github.com/yourusername/usepopcorn](https://github.com/yourusername/usepopcorn)

---

⭐ If you found this project helpful, please give it a star!
