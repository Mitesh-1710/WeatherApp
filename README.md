
# 🌦️ Weather App

A simple and responsive **Weather Application** built with **JavaScript, HTML, and CSS** that fetches real-time weather data using the **OpenWeatherMap API**.
Users can search for any city and instantly view the current weather conditions including temperature, weather description, and wind speed.

---

## 🚀 Features

* 🔍 Search weather by city name
* 🌡️ Displays current temperature in Celsius
* 🌬️ Shows wind speed
* ☁️ Weather description with icon
* 🎨 Dynamic background images based on weather conditions
* ⌨️ Search using button or **Enter key**

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript (Vanilla JS)**
* **Fetch API**
* **OpenWeatherMap API**

---

## 📂 Project Structure

```
weather-app
│
├── index.html
├── style.css
├── script.js
│
├── images
│   ├── clearsky.jpg
│   ├── cloudy.jpg
│   ├── rain.jpg
│   ├── thunderstorm.jpg
│   ├── snow.jpg
│   └── haze.jpg
│
└── README.md
```

---

## ⚙️ How It Works

1. The user enters a **city name** in the search bar.
2. The app sends a request to the **OpenWeatherMap API**.
3. Weather data is returned in JSON format.
4. The app extracts:

   * City Name
   * Temperature
   * Weather Description
   * Weather Icon
   * Wind Speed
5. The UI updates dynamically with the fetched weather data.
6. The background image changes depending on the weather condition.

---

## 🔑 API Setup

1. Create an account at
   [https://openweathermap.org/](https://openweathermap.org/)

2. Generate an API key.

3. Replace the API key in the script:

```javascript
apiKey: "YOUR_API_KEY"
```

---

## 💡 Example Usage

* Search for cities like:

```
London
New York
Tokyo
Delhi
```

The app will instantly show the **current weather conditions** for the selected city.

---

## 📸 Screenshots (Optional)

You can add screenshots of the app interface here.

```
![App Screenshot](screenshot.png)
```

---

## 📌 Future Improvements

* 📍 Detect user location automatically
* 📅 5-day weather forecast
* 📱 Mobile responsiveness improvements
* 🌙 Dark/Light mode toggle

---

## 📜 License

This project is open source and available under the **MIT License**.
