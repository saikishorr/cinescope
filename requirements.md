Build a complete AI Mood-Based Movie Recommendation Web Application using ONLY:

PHP (Core PHP only)
MySQL
HTML5
CSS3
JavaScript
AJAX
Bootstrap 5

The application must be fully compatible with:

cPanel hosting
Shared hosting
Apache server
PHP 8+

Do NOT use:

React
Next.js
Python
Node.js
Laravel
Vue
Angular
MongoDB
Docker
Express.js

Use JavaScript APIs for all movie-related data.

JavaScript should handle:

Fetching movie data
Movie recommendations
Search suggestions
Posters
Ratings
Genres
Trailers
OTT details
Language data
Subtitle availability

Use AJAX and Fetch API heavily.

PHP should mainly handle:

Authentication
Session management
Watchlist storage
User feedback
Recommendation history
Admin panel
MySQL database operations

Create a smart movie recommendation web app where users can discover movies based on:

REQUIRED FILTERS:

Genre
Language
Group Type
Energy Level

OPTIONAL FILTERS:

Runtime
OTT Platform
IMDb Rating
Release Year
Subtitle Language
Actor

The UI should be simple, modern, fast, and mobile-friendly.

Use JavaScript Fetch API to integrate:

TMDB API
For:
Movie details
Posters
Genres
Ratings
Release dates
Cast
Trailers
YouTube API
For:
Movie trailers
OpenSubtitles API
For:
Subtitle language availability
JustWatch or OTT API
For:
Streaming platform availability

Use JavaScript and AJAX for:

Dynamic movie recommendations
Live search
Filtering movies without page reload
Loading movie cards dynamically
Trailer popups
Watchlist updates
Subtitle checks
OTT availability
Infinite scrolling
Lazy loading posters

Use:

Fetch API
Async/Await
Modular JavaScript files

Create recommendation logic using JavaScript.

Example scoring logic:

score =
genreMatch +
languageMatch +
groupTypeMatch +
energyLevelMatch +
optionalFilters

Show highest scored movies first.

Step 1:
Select Genre

Step 2:
Select Language

Step 3:
Select Group Type
Options:

Alone
Family
Friends
Partner

Step 4:
Select Energy Level
Options:

Light
Medium
Intense

Step 5:
Optional Filters

Step 6:
Show Recommendations Dynamically

If selected audio language is unavailable:

Show message:

“Selected audio language unavailable.”

Then show:
Available subtitles:

English
Hindi
Tamil
Telugu

This feature must work dynamically using APIs.

Home Page
Login/Register
Recommendation Page
Movie Details Page
Watchlist Page
User Dashboard
Admin Dashboard

Display:

Poster
Backdrop
Trailer
Description
Rating
Runtime
Genres
Audio languages
Subtitle languages
OTT platforms
Similar movies
Cast
Director

Users should:

Add to watchlist
Remove from watchlist
Save favorite movies

Store watchlist in MySQL using PHP.

Allow users to:

Like/dislike recommendations
Rate satisfaction
Save feedback

Store feedback in MySQL.

Admin should:

Manage users
View feedback
Manage featured movies
View recommendation analytics

Use:

Dark cinematic Netflix-style design
Bootstrap 5
Responsive layout
Animated movie cards
Hover effects
Glassmorphism UI
Smooth transitions

Use MySQL tables for:

users
watchlist
feedback
ratings
recommendation_history

Movie details should mostly come from APIs.

/public_html
/assets
/css
/js
/images
/ajax
/api
/admin
/includes
/config

index.php
login.php
register.php
recommendations.php
movie-details.php
watchlist.php

Use AJAX for:

Recommendation loading
Search
Filters
Watchlist
Feedback
Dynamic movie loading

Avoid full-page reloads.

Implement:

Prepared statements
Password hashing
Session security
SQL injection prevention
XSS protection

The project must:

Run directly on cPanel
Require no terminal
Require no Node.js runtime
Require no Composer
Be uploadable via File Manager or FTP

Generate:

Full PHP backend
HTML pages
CSS files
JavaScript files
AJAX implementation
MySQL schema
API integration code
Recommendation engine
Admin panel
cPanel deployment guide

Create a complete production-ready movie recommendation web application using PHP, MySQL, HTML, CSS, JavaScript, AJAX, and external movie APIs that can be directly hosted on cPanel shared hosting.
