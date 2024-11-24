This is a backend project based on socket.io and uses leaflet library for tracing the real time location of a person, connect another person with the same link with the same map and let's both the users see the location of each other.
socket.io helps you create a dual communication websocket channel between the users with the same current link of the application. Any change on the either end is reflected to other users as well.
The project utilizes the geolocation property of the browser to gain the precise latitude and longitude of the users and feed it to the map coordinates due to which the location shows up on the map.
Ejs is used as view engine for server side rendering and provides the base for changes in the map to be displayed.
