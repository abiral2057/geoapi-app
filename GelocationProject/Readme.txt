## geoFindMe

**geoFindMe** is a JavaScript function that uses the Geolocation API to find the user's current location. It returns the user's latitude and longitude coordinates, which can then be used to display a map or get other information about the user's location.

**Usage:**

```javascript
geoFindMe()


This will call the function and start the process of finding the user's location. Once the function has finished, it will return the user's latitude and longitude coordinates. You can then use these coordinates to display a map or get other information about the user's location.

The geoFindMe function takes no parameters and returns an object with two properties: latitude and longitude. The latitude property is the user's latitude coordinate, and the longitude property is the user's longitude coordinate.

**Example:**

```javascript
// Get the user's latitude and longitude coordinates
const coordinates = geoFindMe();

// Display the user's location on a map
const map = new google.maps.Map(document.getElementById("map"), {
  center: coordinates,
  zoom: 15
});
