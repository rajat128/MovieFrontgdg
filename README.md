# Movies App Frontend<br/>
# Overview<br/>
This is the frontend of the Movies App, built using React with Vite and styled using Tailwind CSS. It provides an interactive user interface for interacting with the RESTful Movies API, allowing users to search, filter, and manage movie data.<br/>

# Features<br/>
User Authentication: Allows users to register and log in.<br/>
Movie Management: Users can create, view, update, and delete movies.<br/>
Filtering: Users can filter movies by title, genre, and release year.<br/>

# Tech Stack<br/>
React: For building user interfaces.<br/>
Vite: For a fast development environment.<br/>
Tailwind CSS: For styling the application.<br/>
Axios: For making HTTP requests to the backend API.<br/>

# Clone the repository:<br/>
git clone https://github.com/yourusername/movies-app-frontend.git<br/>
cd movies-app-frontend<br/>

# Usage<br/>
 Register a User: Use the registration form to create a new account.<br/>
Login: After registration, log in to access movie management features.<br/>
Manage Movies: Create new movies, view the list, update details, and delete movies as needed.<br/>
Filter Movies: Use the filtering options to narrow down the movie list by title, genre, or year.<br/>

#Example API Calls<br/>
The frontend interacts with the backend API using the following functions:<br/>

 Register User: registerUser(userData)<br/>
Login User: loginUser(userData)<br/>
Get Movies: getMovies()<br/>
Create Movie: createMovie(movieData, token)<br/>
Update Movie: updateMovie(id, movieData, token)<br/>
Delete Movie: deleteMovie(id, token)<br/>
Filter Movies: filter(title, genre, year)<br/>
# Contributing<br/>
Contributions are welcome! If you have suggestions or improvements, please create a pull request.<br/>
