# Real-Time Weather Dashboard

A MERN stack app that shows a 5-day weather forecast for any city using the OpenWeatherMap Forecast API.

---

**Features:**  
- Search for any city  
- Displays 5-day forecast (in 3-hour intervals)  
- Shows temperature, weather conditions, icons, humidity, and wind  
- Handles errors for invalid or empty inputs  
- Clean, responsive UI

---

**Tech Stack:**  
- **Frontend:** React, Axios  
- **Backend:** Node.js, Express, Axios, dotenv  
- **API:** OpenWeatherMap Forecast API (<https://openweathermap.org/forecast>)

---

**Setup Instructions:**  

1. *Clone the repository*

2. *Backend Setup:*

   ```bash
   cd server
   npm install
   ```

   Create a file named `.env` inside the `server` folder and add:
   
   ```
   OPENWEATHER_API_KEY=your_api_key_here
   ```

   Start the backend server:

   ```bash
   node server.js
   ```

   The backend will run at `http://localhost:5000`.

3. *Frontend Setup:*

   Open a new terminal window/tab:

   ```bash
   cd client
   npm install
   npm start
   ```

   The React app will run at `http://localhost:3000`.

---

**Project Structure:**  

```
weather-dashboard/
├── client
│   ├── package.json
│   ├── public
│   │   └── index.html
│   └── src
│       ├── App.js
│       ├── components
│       │   ├── SearchBar.jsx
│       │   └── WeatherCard.jsx
│       ├── index.css
│       └── index.js
└── server
    ├── package.json
    ├── routes
    │   └── weather.js
    └── server.js
```

---

