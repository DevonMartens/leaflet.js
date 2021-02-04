# leaflet.js


An excellent rescource for mapping locations and finding corredence:
 
http://geojson.io/#map=2/20.0/0.0


Parts of Leaflet.js to learn

Popups and icons
Shapes and Basics
GeoJSONs
Bounds
Events 
Design

[Markers with custom icons](https://leafletjs.com/examples/custom-icons/) [more on custom icons](https://www.tutorialspoint.com/leafletjs/leafletjs_markers.htm)

```var myIcon = L.icon({
iconUrl: 'my-icon.png',
iconSize: [38, 95],
iconAnchor: [22, 94],
popupAnchor: [-3, -76],
shadowUrl: 'my-icon-shadow.png',
shadowSize: [68, 95],
shadowAnchor: [22, 94]
});
L.marker([50.505, 30.57], {icon: myIcon}).addTo(map);