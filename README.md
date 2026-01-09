# 🌤️ React Weather App

This is a responsive and visually engaging weather application built with **React.js** that fetches real-time weather data using the **OpenWeatherMap API**. The app dynamically updates the background based on current weather conditions and displays temperature, humidity, wind speed, and animated weather visuals, along with real-time date and clock.

## 🚀 Features

- 🌍 Search for weather by city name
- 🌡️ Displays current temperature (in °C)
- 💧 Shows humidity, wind speed, and "feels like" temperature
- 🕒 Real-time clock and date display
- 🎨 Dynamic background images based on weather conditions
- ⚡ Weather condition updates with API integration

## 🔧 Technologies Used

- React.js (Functional Components + Hooks)
- Axios for API calls
- OpenWeatherMap API
- CSS for styling and layout
- React Animated Weather (optional for animated icons)

## 🖼️ Weather Visuals

The app includes background images for the following weather conditions:
- Clear
- Clouds
- Rain
- Snow
- Haze
- Mist
- Fog
- Smoke
- Thunderstorm
- Dazzle (custom)

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Demonking-13/Weather-app.git
   cd react-weather-app

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm start
   ```

4. **Open in Browser**
   Visit `http://localhost:3000` to view your app.

## 🔑 API Key Setup

This app uses the **OpenWeatherMap API**. To get started:

1. Sign up at [OpenWeatherMap](https://openweathermap.org/api)
2. Generate your API key
3. Replace the API key in the `url` variable inside `App.js`:

   ```js
   const url = `https://api.openweathermap.org/data/2.5/weather?q=${location}&units=imperial&appid=YOUR_API_KEY_HERE`;
   ```

## 📁 Project Structure

```
├── public/
├── src/
│   ├── assets/                # Weather background images
│   ├── App.js                 # Main component
│   ├── index.js               # React entry point
│   └── index.css              # Global styling
├── .gitignore
├── package.json
└── README.md
```


## ✨ Future Improvements

* Add weekly forecast feature
* Include animated icons with ReactAnimatedWeather
* Enable geolocation-based weather search
* Add dark/light mode toggle

## 👨‍💻 Author

**Devjit chowdhury**
📫 Connect with me on [LinkedIn](https://www.linkedin.com/in/devjit-chowdhury-77bba3248/) | [GitHub](https://github.com/Demonking-13) |[Gmail](devjitchowdhury2003@gmail.com)

---

**Made with ❤️ using React**


