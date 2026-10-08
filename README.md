# 🌤️ Weatherly

<p align="center">
  <img src="https://img.shields.io/badge/Weatherly-Real--Time%20Weather%20App-4F8EF7?style=for-the-badge" alt="Weatherly">
</p>

<p align="center">
  A modern, responsive weather application built with React.js that provides real-time weather information with dynamic weather-based visuals.
</p>

<p align="center">
  <a href="https://weatherly-phi-one.vercel.app/">
    <img src="https://img.shields.io/badge/🌐%20Live%20Demo-Visit%20Weatherly-000000?style=for-the-badge" alt="Live Demo">
  </a>
  &nbsp;
  <a href="https://github.com/adarshgosavi/Weatherly">
    <img src="https://img.shields.io/badge/⭐%20GitHub-Repository-181717?style=for-the-badge&logo=github" alt="GitHub">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React.js-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/OpenWeather%20API-FF6B35?style=flat-square" alt="OpenWeather">
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel">
</p>

---

## 🌐 Live Demo

🚀 **Live Website:**

### https://weatherly-phi-one.vercel.app/

📂 **Source Code:**

### https://github.com/adarshgosavi/Weatherly

---

## 📸 Preview

> Add your application screenshots inside a `screenshots` folder and update the paths below.

<p align="center">
  <img src="./screenshots/weatherly-dashboard.png" alt="Weatherly Dashboard" width="850">
</p>

<p align="center">
  <i>Weatherly — Real-time weather dashboard</i>
</p>

---

## ✨ Features

| Feature                    | Description                                            |
| -------------------------- | ------------------------------------------------------ |
| 🔍 **City Search**         | Search for weather information by city name            |
| 💡 **Search Suggestions**  | Displays suggestions while searching for a location    |
| 🌡️ **Temperature**        | Shows current temperature with unit conversion support |
| ☁️ **Weather Condition**   | Displays the current weather condition                 |
| 💧 **Humidity**            | Shows current humidity percentage                      |
| 💨 **Wind Information**    | Displays wind speed and direction                      |
| 👁️ **Visibility**         | Shows atmospheric visibility                           |
| 🌅 **Sunrise**             | Displays local sunrise time                            |
| 🌇 **Sunset**              | Displays local sunset time                             |
| 🌦️ **Dynamic Background** | Background changes according to weather conditions     |
| ☀️ **Day/Night Detection** | Weather visuals adapt to the time of day               |
| 📱 **Responsive UI**       | Designed for desktop, tablet and mobile devices        |
| ⚡ **Fast Development**     | Built using Vite for a fast development experience     |
| ❌ **Error Handling**       | Handles invalid searches and API-related errors        |

---

## 🎨 Dynamic Weather Experience

Weatherly changes its visual experience according to the current weather condition.

```text
                 Weather API
                      │
                      ▼
              Weather Condition
                      │
          ┌───────────┼───────────┐
          ▼           ▼           ▼
        Clear       Clouds       Rain
          │           │           │
          ▼           ▼           ▼
       ☀️ Visual    ☁️ Visual    🌧️ Visual
          │           │           │
          └───────────┼───────────┘
                      ▼
                Weatherly UI
```

Supported visual conditions include:

* ☀️ Clear
* 🌙 Clear Night
* ☁️ Clouds
* 🌧️ Rain
* ⛈️ Thunderstorm
* ❄️ Snow
* 🌫️ Fog / Haze

---

## 🧠 How It Works

```text
User
 │
 │  Searches for a city
 ▼
Weatherly React App
 │
 │  API Request
 ▼
OpenWeather API
 │
 │  Weather Data
 ▼
React State
 │
 ├── Temperature
 ├── Humidity
 ├── Wind
 ├── Visibility
 ├── Sunrise / Sunset
 └── Weather Condition
          │
          ▼
   Dynamic UI & Background
```

### Application Flow

1. User enters a city name.
2. Weatherly processes the search request.
3. The application sends a request to the OpenWeather API.
4. Weather data is received from the API.
5. React state is updated with the latest information.
6. Weather details are displayed in the UI.
7. The background and visual elements change according to the weather condition and time of day.

---

## 🛠️ Tech Stack

### Frontend

* **React.js** — Component-based UI development
* **JavaScript (ES6+)** — Application logic
* **HTML5** — Page structure
* **CSS3** — Custom styling and animations
* **Tailwind CSS** — Responsive UI styling
* **Vite** — Development server and production build

### API

* **OpenWeather API** — Real-time weather data

### Deployment & Version Control

* **Vercel** — Deployment
* **Git** — Version control
* **GitHub** — Source code hosting

---

## ⚛️ React Concepts Used

Weatherly was developed using several important React concepts:

### Hooks

```javascript
useState()
useEffect()
```

### Component-Based Architecture

The application separates reusable functionality into components such as:

```text
WeatherBackground
Icons
Helper
```

### State Management

Application state is used for:

* Weather data
* City search
* Search suggestions
* Temperature unit
* API errors
* Day/night status

### Conditional Rendering

The UI dynamically responds to:

* Weather conditions
* Day/night state
* API response
* Search state
* Error state

---

## 📁 Project Structure

```text
Weatherly/
│
└── Weathers-app/
    │
    ├── public/
    │
    ├── src/
    │   │
    │   ├── assets/
    │   │   └── Weather animations & assets
    │   │
    │   ├── components/
    │   │   ├── Helper.jsx
    │   │   ├── Icons.jsx
    │   │   └── WeatherBackground.jsx
    │   │
    │   ├── App.jsx
    │   ├── main.jsx
    │   └── index.css
    │
    ├── .env
    ├── .gitignore
    ├── package.json
    ├── package-lock.json
    ├── vite.config.js
    └── README.md
```

---

## ⚙️ Installation

Want to run Weatherly locally?

### 1. Clone the repository

```bash
git clone https://github.com/adarshgosavi/Weatherly.git
```

### 2. Navigate to the project

```bash
cd Weatherly/Weathers-app
```

### 3. Install dependencies

```bash
npm install
```

### 4. Create environment variables

Create a `.env` file in the project root:

```env
VITE_WEATHER_API_KEY=your_openweather_api_key
```

Replace `your_openweather_api_key` with your actual OpenWeather API key.

### 5. Start the development server

```bash
npm run dev
```

The application will be available at:

```text
http://localhost:5173
```

---

## 🔐 Environment Variables

Weatherly uses an environment variable for the OpenWeather API key.

```env
VITE_WEATHER_API_KEY=your_openweather_api_key
```

### Important

**Never commit your API key to GitHub.**

Make sure your `.gitignore` contains:

```text
.env
.env.local
```

---

## 📡 API Integration

Weatherly uses the **OpenWeather API** to retrieve current weather information.

The application uses weather data to display:

```text
Temperature
Weather Condition
Humidity
Wind Speed
Wind Direction
Visibility
Sunrise
Sunset
City Information
```

The received API response is processed and converted into user-friendly information before being displayed.

---

## 📱 Responsive Design

Weatherly is designed to work across multiple screen sizes.

```text
💻 Desktop
     ↓
💻 Laptop
     ↓
📱 Tablet
     ↓
📱 Mobile
```

The interface adapts to different screen sizes while keeping the weather information easy to read and interact with.

---

## 🚀 Deployment

Weatherly is deployed using **Vercel**.

### Production Website

👉 **[Open Weatherly](https://weatherly-phi-one.vercel.app/)**

The project can be connected to GitHub and deployed automatically through Vercel.

---

## 🧪 Challenges & Solutions

### 🌐 API Integration

**Challenge:** Handling asynchronous weather API requests and displaying the returned data correctly.

**Solution:** Used React state and `useEffect()` to manage API requests and update the interface.

### 🌦️ Dynamic Backgrounds

**Challenge:** Creating different visual experiences for different weather conditions.

**Solution:** Created a dedicated `WeatherBackground` component that selects visuals based on weather condition and day/night status.

### 🌡️ Data Formatting

**Challenge:** Raw API data is not always suitable for direct display.

**Solution:** Created helper functions for converting and formatting values such as temperature, humidity, visibility and wind direction.

### 📱 Responsive Interface

**Challenge:** Maintaining a clean interface across different screen sizes.

**Solution:** Used responsive CSS/Tailwind utilities and flexible layouts.

### 🚀 Production Deployment

**Challenge:** Configuring the project correctly for production deployment.

**Solution:** Configured the Vite project and deployed the application through Vercel.

---

## 📚 What I Learned

Building Weatherly helped me gain practical experience in:

* ⚛️ React.js development
* 🧩 Reusable components
* 🎣 React Hooks
* 🔌 REST API integration
* 🔄 Asynchronous JavaScript
* 🧠 State management
* 🎨 Tailwind CSS
* 📱 Responsive web design
* 🔐 Environment variables
* 🐛 Error handling
* 🐙 Git & GitHub
* 🚀 Vercel deployment
* 🔧 Debugging production issues

---

## 🔮 Future Roadmap

The following features can be added in future versions:

* [ ] 📅 5-Day Weather Forecast
* [ ] 📍 Current Location Weather
* [ ] ⭐ Favorite Cities
* [ ] 🌡️ Celsius / Fahrenheit Toggle
* [ ] 🗺️ Interactive Weather Map
* [ ] 📊 Weather Charts & Graphs
* [ ] 🔔 Weather Alerts
* [ ] 🌍 Multi-Language Support
* [ ] 🌓 Improved Light / Dark Theme
* [ ] 📈 Historical Weather Data

---

## 🤝 Contributing

Contributions are welcome!

If you have an idea or improvement:

### Fork the repository

```bash
git clone https://github.com/adarshgosavi/Weatherly.git
```

### Create a feature branch

```bash
git checkout -b feature/your-feature
```

### Make your changes

```bash
git add .
git commit -m "Add: your feature"
```

### Push your branch

```bash
git push origin feature/your-feature
```

Then create a Pull Request.

---

## ⭐ Show Your Support

If you like this project, consider:

⭐ **Giving the repository a star**

🍴 **Forking the repository**

🐛 **Reporting bugs**

💡 **Suggesting new features**

---

## 👨‍💻 Author

### Adarsh Gosavi

**Frontend Developer | React.js Developer**

<p>
  <a href="https://github.com/adarshgosavi">
    <img src="https://img.shields.io/badge/GitHub-Adarsh%20Gosavi-181717?style=for-the-badge&logo=github" alt="GitHub">
  </a>
</p>

---

## 📄 License

This project is created for **educational and portfolio purposes**.

---

<p align="center">
  <b>🌤️ Weatherly</b>
  <br>
  Real-time weather information, beautifully presented.
  <br><br>
  ⭐ <b>Star the repository if you like it!</b>
</p>
