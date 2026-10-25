VILOYATGA BORAMIZ — PROJECT FILES

Included:
- index.html: the website, including its CSS and JavaScript.
- assets/Man waiting car.webm: the first-visit introduction video.

HOW TO RUN
1. Extract the entire ZIP into one folder.
2. Keep the assets folder beside index.html. Do not move index.html out of the folder.
3. Open index.html in Chrome or Edge while connected to the internet.
4. For location permission, browser geolocation may require localhost/HTTPS instead of opening the file directly. If needed, run a local server from this folder:
   Windows (Python installed): py -m http.server 8000
   Then open http://localhost:8000

IMPORTANT
- The map uses Leaflet from a CDN and OpenStreetMap tiles, so an internet connection is required for the map.
- This is a front-end prototype. Sign-in, driver announcements, and bookings are stored in this browser/device only; they are not shared with other users or devices.
- The ZIP contains the current website source and its video asset. It does not include a deployed website or a live backend/database.
