# Mate Maps

Mate Maps is a small web app to find nearby places that sell mate (supermarkets, kiosks, cafés, etc.).  
It uses OpenStreetMap data and Firebase so you can discover, add, and rate mate spots around you.

Features
- Interactive Leaflet map with a dark / gold UI.
- Search from the home page by city or ZIP code.
- Optional geolocation to center the map near your current position.
- Adjustable search radius for supermarkets.
- Custom places: add your own mate spots with name, description and a 1–5 “Mate score”.
- Community ratings for both supermarkets and custom places, stored in Firebase.

Tech Stack
- HTML, CSS, vanilla JavaScript
- Leaflet for maps and markers
- OpenStreetMap + Overpass API for supermarket data
- Nominatim for geocoding search queries
- Firebase Firestore for custom places and ratings

Project Structure
- index.html – Landing page with hero section and search box that forwards to the map (`src/pages/map.html?q=...`).
- map.html – Main map experience: search, radius slider, custom place form, ratings, and sidebar list.
- about.html – About / privacy / contact information.
- root.css – Global theme (colors, navigation, background glow).
- index.css – Home page / hero styles.
- map.css – Map layout, sidebar, markers, and responsive behavior.
- about.css – About page layout and cards.

Contributions
Issues, suggestions, and pull requests are welcome.  
If you know of great mate spots that are missing or want to tweak the UI/UX, feel free to open an issue or PR.
