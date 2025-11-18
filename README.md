# 🌦️ Weather App — Built by Arnav Anand

A modern, glass-morphic, feature-rich weather application powered by Open-Meteo Weather, Air Quality, and Geocoding APIs.  
This app provides real-time weather, AQI, 5-day forecasts, autosuggest search, favorites saving, and more — all inside a beautifully animated UI.

---

## 🎯 Features

### 1. Live Weather Data (Current + 5-Day Forecast)
- Real-time temperature, conditions, humidity, pressure, UV index, wind, sunrise & sunset  
- 5-day forecast with min/max temperatures and weather codes

### 2. Air Quality Index (AQI)
- Fetches US AQI, PM10, PM2.5  
- Displays AQI level and category

### 3. Smart Location Search + Auto-Suggestions
- Search by city, ZIP, landmark, or coordinates  
- Live autosuggest powered by Open-Meteo Geocoding API

### 4. Temperature Unit Toggle (°C ⇆ °F)
- Converts all temperatures instantly  
- Preference saved locally

### 5. Favorites System (Local Storage)
- Save any location  
- Click to reload weather instantly

### 6. Use My Location (GPS)
- Auto-detect user coordinates  
- Fetches weather for exact location

### 7. Real-Time Clock + Auto Dark Mode
- Live clock updates per second  
- Theme changes based on day/night time

### 8. Modern Glassmorphism UI
- Smooth animated gradient background  
- Frosted glass weather cards  
- Responsive design

### 9. PM Accelerator Info Modal
- Info button shows details about the Product Manager Accelerator Program

---

## 🛠️ Tech Stack

| Area | Technology |
|------|------------|
| Frontend | HTML5, CSS3, JavaScript |
| APIs | Open-Meteo Weather API, Geocoding API, Air Quality API |
| Storage | LocalStorage |

---

## 📡 APIs Used

### Geocoding API
### Weather API
### Air Quality API

---

## 📘 How the App Works

### Step 1 — Enter Location
- Type a city or coordinates  
- Autosuggest options appear  
- Or use "Use My Location"

### Step 2 — Weather Loads
Displays:  
Temperature, weather code, humidity, pressure, UV index, wind, sunrise/sunset.

### Step 3 — View 5-Day Forecast
Each day card includes emoji, min/max temperature, and rain probability.

### Step 4 — Save Favorite Locations
Favorites are stored in browser local storage.

### Step 5 — View PM Accelerator Info
Click the info button to open the modal.

---

## 🧭 Supported Inputs

**Cities:**  
Delhi, Mumbai, London, Tokyo

**Coordinates:**  
28.6,77.2  
19.07,72.87

---

## 🧩 Key JavaScript Highlights

- Uses `Promise.all()` to fetch weather + air quality in parallel  
- Temperature conversion without refetching  
- LocalStorage implementation  
- Debounced autosuggest search  
- Weather emoji mapping based on weather codes  

---

## 📱 Responsive Design

The UI adapts smoothly across:  
- Mobiles  
- Tablets  
- Desktop screens

---

## 👤 Developer: Arnav Anand

Part of learning goals in:  
- Frontend development  
- API integration  
- UI/UX design

---

## ⭐ Future Enhancements

- Hourly forecast  
- Weather alerts  
- Live radar maps  
- Animated icons  
- Multi-theme support  

---

## 📝 License

This project is open-source under the MIT License.

