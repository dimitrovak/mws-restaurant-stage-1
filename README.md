# FEND Restaurant Review App

## Project Overview: Stage 1
Convert a static webpage to a responsive accessible web application. Utilize the function of a service worker to create a seamless offline experience.
 
### Functionality
The web application allows the user to browse through a list of restaurants using location and cuisine type filters. The user can also pick a restaurant directly from the provided map. Each restaurant's page includes a map with the restaurant's location, a picture from inside the restaurant, open hours and reviews.

### How to use the web application?
 - Clone the repository - https://github.com/dimitrovak/mws-restaurant-stage-1
 - CD into the folder mws-restaurant-stage-1
 - Run the server using the following command: python -m http.server 8000
 - Type in your browser: http://localhost:8000/   and Voilà! you now have access to the Restaurant Reviews App :)

### Project Structure
 - The main page is index.html
 - The restaurant's details page is restaurant.html
 - The CSS file is styles.css
 - The JS file for the main page is main.js
 - The JS file for the restaurant page is restaurant_info.js
 - The JS file to fetch the data from the server is dbhelper.js
 - The service worker file is service-worker.js and it is registered in the main.js file.
 - All images are located in img folder. 
