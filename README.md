# 🌤️ Weatherly

### Modern Real-Time Weather Application

<p align="center">
  <b>Search any city and get beautiful, real-time weather information with dynamic weather visuals.</b>
</p>

<p align="center">
  <a href="https://weatherly-phi-one.vercel.app/">
    <img src="https://img.shields.io/badge/🌐%20Live%20Demo-Weatherly-blue?style=for-the-badge" alt="Live Demo">
  </a>
  <a href="https://github.com/adarshgosavi/Weatherly">
    <img src="https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github" alt="GitHub">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React.js-18+-61DAFB?style=flat-square&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/Tailwind%20CSS-4.x-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white">
  <img src="https://img.shields.io/badge/Vite-Latest-646CFF?style=flat-square&logo=vite&logoColor=white">
  <img src="https://img.shields.io/badge/Vercel-Deployed-black?style=flat-square&logo=vercel">
</p>

---

## 🌐 Live Demo

### 🚀 [Visit Weatherly](https://weatherly-phi-one.vercel.app/)

---

## 📖 About

**Weatherly** is a modern, responsive weather application built with **React.js** that provides real-time weather information for cities around the world.

The application integrates the **OpenWeather API** to retrieve current weather data and transforms it into a clean, intuitive interface.

Weatherly also provides **dynamic weather backgrounds** that adapt to the current weather condition and time of day, creating a more immersive user experience.

---

## ✨ Key Features

<table>
<tr>
<td width="50%">

### 🔍 Smart Search

Search for weather information by entering a city name with suggestion support.

### 🌡️ Current Weather

View the current temperature and weather condition in real time.

### 💧 Humidity

Get the current humidity percentage for the selected location.

### 💨 Wind Information

View wind speed and direction.

</td>
<td width="50%">

### 👁️ Visibility

Check the current atmospheric visibility.

### 🌅 Sunrise & Sunset

View accurate sunrise and sunset times.

### 🌦️ Dynamic Weather UI

Weather backgrounds and visuals change according to current conditions.

### 📱 Responsive Design

Optimized for desktop, laptop, tablet, and mobile devices.

</td>
</tr>
</table>

---

## 🎨 Weather Experience

Weatherly dynamically adapts its interface according to the current weather.

| Weather Condition | Experience                     |
| ----------------- | ------------------------------ |
| ☀️ Clear          | Bright and sunny environment   |
| ☁️ Clouds         | Animated cloudy environment    |
| 🌧️ Rain          | Dynamic rain visuals           |
| ⛈️ Thunderstorm   | Lightning and storm visuals    |
| ❄️ Snow           | Snowfall animation             |
| 🌫️ Fog / Haze    | Atmospheric background         |
| 🌙 Night          | Night-specific weather visuals |

---

## 🛠️ Tech Stack

### Frontend

| Technology          | Purpose                       |
| ------------------- | ----------------------------- |
| ⚛️ **React.js**     | UI development                |
| 🟨 **JavaScript**   | Application logic             |
| 🎨 **Tailwind CSS** | Styling and responsive design |
| ⚡ **Vite**          | Development and build tool    |
| 🧱 **HTML5**        | Application structure         |
| 🎨 **CSS3**         | Custom styling and animations |

### API & Deployment

| Technology              | Purpose                |
| ----------------------- | ---------------------- |
| 🌤️ **OpenWeather API** | Real-time weather data |
| ▲ **Vercel**            | Production deployment  |
| 🐙 **GitHub**           | Version control        |

---

## 🏗️ Project Architecture

```text
                         ┌─────────────────────┐
                         │       Weatherly     │
                         │      React App      │
                         └──────────┬──────────┘
                                    │
                         ┌──────────▼──────────┐
                         │     User Search     │
                         │       / City        │
                         └──────────┬──────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │   OpenWeather API   │
                         └──────────┬──────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │   Weather Response  │
                         └──────────┬──────────┘
                                    │
                  ┌─────────────────┼─────────────────┐
                  ▼                 ▼                 ▼
           ┌────────────┐    ┌────────────┐    ┌────────────┐
           │ Temperature│    │   Details  │    │  Condition │
           │            │    │ Humidity   │    │   Weather  │
           │            │    │ Wind       │    │ Background │
           └────────────┘    └────────────┘    └────────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │   Dynamic Weather   │
                         │         UI          │
                         └─────────────────────┘
```

---

## 📂 Project Structure

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
    │   │   └── weather animations
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

## ⚙️ Getting Started

Follow these steps to run Weatherly locally.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/adarshgosavi/Weatherly.git
```

### 2️⃣ Navigate to the Project

```bash
cd Weatherly/Weathers-app
```

### 3️⃣ Install Dependencies

```bash
npm install
```

### 4️⃣ Configure Environment Variables

Create a `.env` file in the project root:

```env
VITE_WEATHER_API_KEY=your_openweather_api_key
```

> ⚠️ **Never commit your API key to GitHub.**

Make sure `.env` is included in `.gitignore`:

```text
.env
.env.local
```

### 5️⃣ Start Development Server

```bash
npm run dev
```

Open:

```text
http://localhost:5173
```

---

## 🔑 API Configuration

Weatherly uses the **OpenWeather API** to retrieve current weather information.

The application uses API data to display:

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

---

## 🧠 React Concepts Used

This project was also built to practice real-world React development concepts.

### React Hooks

```javascript
useState()
useEffect()
```

### State Management

Weatherly manages application state for:

* Weather data
* City search
* Search suggestions
* Temperature unit
* API errors
* Day/night detection

### Conditional Rendering

The UI dynamically changes based on:

```text
Weather Condition
Day / Night
API Response
Search State
Error State
```

---

## 📱 Responsive Design

Weatherly is designed to provide a consistent experience across different devices.

```text
Desktop        ████████████████████
Laptop         ████████████████████
Tablet         ████████████████████
Mobile         ████████████████████
```

---

## 🚀 Deployment

The application is deployed on **Vercel**.

### Production

🔗 **https://weatherly-phi-one.vercel.app/**

Every production build can be deployed directly from the GitHub repository through Vercel.

---

## 📸 Screenshots

> Add screenshots of your application here to make the repository more visually attractive.

### 🏠 Weather Dashboard

```text
Add your screenshot here
```

### 🌧️ Rain Weather

```text
Add your screenshot here
```

### 📱 Mobile View

```text
Add your mobile screenshot here
```

Once screenshots are added, use:

```markdown
![Weatherly Dashboard](./screenshots/dashboard.png)
```

---

## 🔮 Future Improvements

Weatherly can be extended with additional features:

* [ ] 📅 5-day weather forecast
* [ ] 📍 Current location weather
* [ ] ⭐ Favorite cities
* [ ] 🌡️ Celsius / Fahrenheit toggle
* [ ] 🗺️ Interactive weather map
* [ ] 📊 Weather charts
* [ ] 🔔 Severe weather alerts
* [ ] 🌍 Multi-language support
* [ ] 🌓 Improved theme support
* [ ] 📈 Historical weather data

---

## 📚 Learning Outcomes

Building Weatherly helped strengthen practical knowledge of:

* ⚛️ React.js
* 🟨 Modern JavaScript
* 🔌 REST API integration
* 🔄 Asynchronous programming
* 🎣 React Hooks
* 🧠 State management
* 🎨 Tailwind CSS
* 📱 Responsive design
* 🌐 Environment variables
* 🐙 Git & GitHub
* 🚀 Vercel deployment
* 🛠️ Debugging production builds

---

## 🧪 Challenges Solved

During development, several real-world frontend challenges were handled, including:

* API data fetching and error handling
* Dynamic weather condition rendering
* Day/night detection
* Dynamic background selection
* Temperature conversion
* Weather data formatting
* Responsive UI design
* Production deployment
* Vercel build configuration

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

### Fork the repository

```bash
git fork https://github.com/adarshgosavi/Weatherly
```

### Create a branch

```bash
git checkout -b feature/new-feature
```

### Commit changes

```bash
git add .
git commit -m "Add new feature"
```

### Push changes

```bash
git push origin feature/new-feature
```

Then open a **Pull Request**.

---

## ⭐ Support

If you found this project useful or interesting:

⭐ **Star the repository**

🍴 **Fork the project**

🐛 **Report issues**

💡 **Suggest improvements**

---

## 👨‍💻 Author

### Adarsh Gosavi

Frontend Developer | React.js Developer

<p>
  <a href="https://github.com/adarshgosavi">
    <img src="https://img.shields.io/badge/GitHub-Adarsh%20Gosavi-black?style=for-the-badge&logo=github">
  </a>
</p>

---

## 📄 License

This project is developed for **educational and portfolio purposes**.

---

<p align="center">

### 🌤️ Weatherly

**Real-time weather. Beautifully presented.**

⭐ If you like Weatherly, consider giving it a star!

</p>
