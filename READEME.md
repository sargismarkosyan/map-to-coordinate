# Map photo to cordinate converter

The goal is: when given the region map with boundary coordinates be able to get the
coordinate of the device that takes the photo of the map.

### The map characteristics
- Can be vary based on specific region time zone, weather and season.
- Plain a 2D flat image

### The boundary characteristics
- x, y coordinates of the starting point and the ending points of the map.

### Photo characteristics
- A photo of the part of the map from different angle, height, optical distractions,
weather distractions (like fog, light and season)
- Should return the coordinate of photo source