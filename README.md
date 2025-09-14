## ShowMe

### 🚀 Introduction
ShowMe is a full-stack web application designed to help users discover, track, and manage their favorite TV shows—and soon, movies. The goal of the project is to create a personalized entertainment dashboard that’s fast, accessible, and easy to use. By combining clean UI design with robust backend functionality, ShowMe empowers users to explore content, save favorites, and monitor their viewing progress—all in one place.
This project was built to deepen my experience in full-stack development, strengthen my understanding of API integration, and demonstrate how thoughtful engineering can solve real-world user needs.

### What this project does
- Lets anyone discover TV shows with a clean, fast UI.
- Fetches show data (via the backend’s TVmaze proxy) and displays:
  - Paginated lists, cover images, premiere dates, ratings, and genres.
  - A show details modal with summary and star ratings.
- Provides search and genre filters to quickly find content.
- Enables authenticated users to:
  - Save shows to their account (favorites/watchlist).
  - Track progress (e.g., season/episode and related metadata).
  - Edit profile info (username, avatar).
- Uses semantic HTML, ARIA, and BEM-based CSS for accessibility and responsiveness.

### 🔧 Main Body – What Was Done & How
ShowMe was built using the MERN stack (MongoDB, Express, React, Node.js) with a focus on clean architecture, accessibility, and user experience.
🧠 Backend
- Built with Node.js and Express, serving as a proxy to the TVmaze API.
- RESTful endpoints handle user authentication, show tracking, and profile management.
- MongoDB stores user data, favorites, and progress metadata, with Mongoose models for validation.
- JWT tokens manage secure login and session persistence.
🎨 Frontend
- Developed using React, with functional components and hooks.
- Navigation handled via React Router.
- Styled using BEM-based CSS for modularity and responsiveness.

## 📈 Business Outcomes
- Streaming Integration: Partner with streaming platforms to link directly to content, driving engagement and affiliate revenue.
- Premium Features: Offer paid tiers with advanced tracking, analytics, or curated recommendations.
- Data Insights: Aggregate anonymized user trends to help studios understand what audiences are watching and loving.
- Brand Collaborations: Allow entertainment brands to sponsor curated lists or seasonal content collections.


 ### 🆕 Upcoming Movie Features
- Integrate a movie data API (e.g., TMDb or OMDb) alongside TVmaze.
- Display movie-specific metadata: runtime, release year, director, cast, etc.
- Add movie detail modals with trailers and ratings.
- Enable users to save and review movies in their watchlist.
- Filter movies by genre, release year, and popularity.
- Unified search across TV and movie content
- Personalized recommendations based on user activity
- Dark mode toggle
- Social features (e.g., share lists, follow users)
- Performance optimizations and mobile-first enhancement

## 🏁 Conclusion
ShowMe started as a way to sharpen my full-stack skills, and it turned into something I’m genuinely proud of. It’s clean, responsive, and solves a real user need. Along the way, I learned a ton about building scalable features, working with APIs, and designing for real people. And with movies on the way, it’s just getting started.


  ## Pictures
  Profile Page
<img width="1914" height="935" alt="image" src="https://github.com/user-attachments/assets/372dc5f4-3bc2-4df6-8961-93a17c0f5325" />

Shows Page
<img width="1903" height="921" alt="image" src="https://github.com/user-attachments/assets/b5bd3101-69de-469e-942c-c70dc3fd3d9f" />


