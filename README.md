# Real-Time Location Tracker

A real-time location tracking web application built using Node.js, Express.js, Socket.IO and Leaflet.js.

## Features

* Get user's live location using the Browser Geolocation API
* Send location updates in real time
* Display location on an interactive map
* Track multiple connected users
* Remove users when they disconnect

## Technologies Used

* Node.js
* Express.js
* Socket.IO
* EJS
* JavaScript
* Leaflet.js
* OpenStreetMap

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/pratikshabpare/real-time-location-tracker.git
```

### 2. Go to the project folder

```bash
cd real-time-location-tracker
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the server

```bash
node app.js
```

You can also use Nodemon:

```bash
npx nodemon app.js
```

### 5. Open in browser

```text
http://localhost:3000
```

## How It Works

1. The browser gets the user's latitude and longitude using the Geolocation API.
2. Socket.IO sends the location data to the Node.js server.
3. The server broadcasts the location to connected users.
4. Leaflet.js displays the location on an interactive map.
5. When a user disconnects, their marker is removed.

## Project Structure

```text
real-time-location-tracker/
├── app.js
├── package.json
├── package-lock.json
├── README.md
├── .gitignore
├── views/
│   └── index.ejs
└── public/
    ├── css/
    │   └── style.css
    └── js/
        └── script.js
```

## Future Improvements

* User authentication
* Location history
* Distance calculation
* Route tracking
* Mobile-friendly interface
* Database integration
