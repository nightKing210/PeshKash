🎬 PeshKash – Your Gateway to Movies

PeshKash is a simple, elegant, and responsive web application that lets users explore detailed movie information powered by the OMDb API
.
Built with pure HTML, JavaScript, and TailwindCSS, PeshKash offers a smooth, cinematic experience for film lovers.

🌟 Features

🔍 Instant Movie Search — Search any movie by name and get real-time results.

🎞️ Detailed Information — Displays title, release year, genre, runtime, director, plot, and more.

🏆 Awards & Ratings — See IMDb ratings, votes, and award history at a glance.

💰 Box Office Info — Get an idea of a movie’s commercial success.

🖼️ Poster Display — High-quality movie poster fetched automatically.

📱 Responsive Design — Works beautifully on desktop, tablet, and mobile.

⚙️ Tech Stack
Technology	Purpose
HTML5	Structure of the website
Tailwind CSS	Styling and layout
JavaScript (ES6)	Dynamic movie fetching and rendering
OMDb API	Source of all movie data
🚀 How It Works

The user enters a movie name in the search bar.

A fetch() request is sent to the OMDb API endpoint:

https://www.omdbapi.com/?apikey=YOUR_API_KEY&t=MovieName


The response (JSON format) includes all the movie data:

Title, Year, Released Date

Genre, Director, Plot, Language

Awards, IMDb Rating, Votes, Box Office, and Poster

The information is then dynamically displayed on the page with smooth transitions.

🧠 Example Output

Searching for Inception shows:

Title: Inception
Year: 2010
Director: Christopher Nolan
Genre: Action, Adventure, Sci-Fi
IMDb Rating: ⭐ 8.8
Box Office: $829,895,144
Awards: Won 4 Oscars. 157 wins & 220 nominations total

💡 Inspiration

The name “PeshKash” (پیشکش) means “a presentation” or “a gift” in Urdu —
representing the idea of presenting cinematic art to the audience in a simple, accessible way.
