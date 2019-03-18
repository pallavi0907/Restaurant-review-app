# Restaurant Review app

The goal of this project is to implement Responsive design, service worker to cache and Accessibilty.

# Project Overview:

* For the Restaurant Reviews project, we have to incrementally convert a static webpage to a mobile-ready web application. In Stage One, this project is a static design that lacks accessibility and need to convert the design to be responsive on different sized displays and accessible for screen reader use. There is also need to add a service worker to begin the process of creating a seamless offline experience for users.

# How to run the application:

For Users:
* In this website , you can search your choice of restaurant. You can filter your search by location and cuisine type.
* Use dropdown list to filter your result(on the main page)
* You can see the updated map once you change your location.
* You can see the details of the restaurant page once you click on view details page link.
* The restaurant details page includes Map, Cuisine name, Restaurant opening hours and Reviews.

For Developers:
* Clone the repository
* Go to the folder on the desktop where you saved them
* Run the server using the following command
  Python 3

  python -m http.server 8000

* Go to localhost:8000 to open the website.
* The main HTML page is /index.html
* The restaurant's details HTML page is /restaurant.html
* The CSS file is /css/styles.css
* The JS file for the main page is /js/main.js
* The JS file for the restaurant page is /js/restaurant_info.js
* The JS file to fetch the data from the server is /js/dbhelper.js
* The service worker is located in /service-worker.js and registered in the /js/main.js file.

# Leaflet.js and Mapbox:

* This repository uses leaflet.js with Mapbox. we need to replace <your MAPBOX API KEY HERE> with a token from Mapbox. Mapbox is free to use, and does not require any payment information.

# Author

* **Pallavi Paul**
