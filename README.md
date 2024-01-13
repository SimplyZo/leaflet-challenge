# leaflet-challenge

The logic.js file contains JavaScript code for creating an interactive map to display earthquake data. Key features include:

Map Initialization: A map is created using Leaflet, centered at specific coordinates with a defined zoom level.
Base Map Layer: Incorporates a tile layer from ArcGIS for the background, including attribution to Esri and the US National Park Service.
Earthquake Data Retrieval: Fetches earthquake data in GeoJSON format from the USGS website.
Data Visualization: Uses depth and magnitude of earthquakes to determine marker color and radius. Includes a function to style these markers on the map.
Popups: Configures popups to display earthquake magnitude, depth, and location when a marker is clicked.
Legend Creation: Adds a legend to the map, illustrating the color coding for different earthquake depths.

The style.css file is a stylesheet designed for web development, containing CSS rules to define the visual presentation of HTML elements in a webpage. Key aspects include:

Layout and Structure: Defines basic layout properties such as margins, padding, and display types for various HTML elements.
Typography: Specifies font properties, including type, size, and color, enhancing readability and visual appeal.
Color Scheme: Establishes a consistent color palette for the website, including background colors and element coloration.
Responsive Design: Contains media queries to ensure the website is visually appealing and functional across different device sizes.
Interactive Elements: Styles for buttons, links, and other interactive elements, including hover effects for improved user experience.