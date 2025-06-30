# IOT-Weather-Station


A responsive real-time weather dashboard built using ESP32, DHT11, Firebase Realtime Database, and OpenWeatherMap API. The web interface is designed in pure HTML/CSS/JS with Bootstrap and can be hosted using GitHub Pages.

---

## 📌 Features

- ✅ Real-time **local temperature and humidity** readings using DHT11 sensor
- ✅ Fetches live **external weather** from OpenWeatherMap API
- ✅ Stores all data in **Firebase Realtime Database**
- ✅ Minimal, clean web dashboard
- ✅ Separate display for local vs API humidity

---

## 🧠 How It Works

1. The ESP32 reads:
   - Local temperature and humidity from the DHT11 sensor
   - External weather (humidity, pressure, wind speed, etc.) from OpenWeatherMap API

2. The ESP32 pushes all data to Firebase Realtime Database.

3. The dashboard webpage:
   - Connects to Firebase
   - Reads the latest data when the user clicks the refresh button
   - Displays all data in a clean two-column layout using Bootstrap

4. The dashboard also converts the UNIX timestamp to a readable local date/time.

---

## 🌐 Live Demo


---

## 🛠️ Technologies Used
- ESP32 (Arduino + DHT11 sensor)
- Firebase Realtime Database
- OpenWeatherMap API
- HTML, CSS, JavaScript
- Bootstrap 5
- GitHub Pages (hosting)

  
---

## 🧪 Screenshots




