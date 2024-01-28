# BusTrackingSystem

## Overview

This Bus Tracking System is a web application developed using HTML, CSS, and JavaScript. The purpose of this system is to provide a user-friendly interface for tracking the real-time location of buses and retrieving detailed information about them. The system incorporates Google Maps for visualization and uses geolocation to display the user's position on the map.

## Files and Structure

### 1. HTML (index.html)

The HTML file defines the structure of the web page. Key sections include:

- **Header:** Contains the project title, "Bus Tracking System."
- **Content:** Divided into two main parts - the map and bus information.
- **Map Section:** Embedded Google Maps with a designated area for bus markers.
- **Bus Information Section:** Displays a search bar, a list of buses, and relevant details.
- **Footer:** Displays the project's copyright information.

### 2. CSS (style.css)

The CSS file styles the entire web page, providing an aesthetically pleasing and responsive layout. Notable styles include:

- **Background:** Utilizes a cohesive color scheme (#88AB8E, #F2F1EB, #000000) for a visually appealing interface.
- **Layout:** Uses flexbox to structure the page and ensure responsiveness.
- **Bus Information:** Applies styling to input fields, buttons, and bus list items.
- **Map:** Defines the size, border-radius, and shadow for the map container.

### 3. JavaScript (script.js)

The JavaScript file handles the dynamic functionalities of the Bus Tracking System. Key features and functions include:

#### Initialization and User Location

- **Google Maps Initialization:** Sets up the Google Maps API and centers the map on Thiruvananthapuram (TVM).
- **User Marker:** Retrieves the user's geolocation and displays it on the map with a blue marker.

#### Bus Data and Markers

- **Bus Data Array:** Contains details for each bus, including ID, name, latitude, longitude, and route.
- **Bus Markers:** Creates markers for each bus on the map with labels, click events, and route information.
- **Bus Information Display:** Dynamically updates the bus information section with details on user interaction.

#### Geolocation and Distance Calculation

- **Geolocation:** Checks for geolocation support and retrieves the user's current position.
- **Distance Calculation:** Uses the Haversine formula to calculate the distance between two geographical points.

#### Search Functionality

- **Stop Name Mapping:** Defines a mapping between predefined stop names and corresponding stop numbers.
- **Search Buses Function:** Filters buses based on user input (stop name) and updates the UI.


## Dependencies

- **Google Maps API:** Embeds and interacts with Google Maps.
- **Font Awesome:** Provides scalable vector icons for UI enhancement.

## Notes and Customization

- The project uses hardcoded bus data and route stops for demonstration purposes.
- A valid Google Maps API key is necessary for proper map functionality.

## Languages used 
* html
* Css
* Java script


