# 🌤️ React Weather App

> A React weather application that fetches real-time data from OpenWeatherMap API and displays temperature, humidity, and weather conditions with dynamic imagery.

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![MUI](https://img.shields.io/badge/Material--UI-0081CB?style=for-the-badge&logo=mui&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![OpenWeatherMap](https://img.shields.io/badge/OpenWeatherMap-API-orange?style=for-the-badge)

---
## 🌐 Live Demo

🔗 [react-weather-app-seven-mauve.vercel.app](https://react-weather-app-seven-mauve.vercel.app/)
---

## ✨ Features

- 🔍 **Search Weather** — Search real-time weather by any city name
- 🌡️ **Weather Details** — Temperature, humidity, min/max temp and feels-like
- 🖼️ **Dynamic Background** — Background image changes based on weather (hot, cold, rainy)
- ⛅ **Weather Icons** — Sunny, Thunderstorm, Snowflake icons from MUI
- ❌ **Error Handling** — Shows "No such place exists!" for invalid cities
- 📱 **Responsive Design** — Clean card layout using Material UI

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| **Frontend Framework** | React (Vite) |
| **UI Library** | Material UI (MUI v5) |
| **Language** | JavaScript (ES6+) |
| **Styling** | CSS3 |
| **API** | OpenWeatherMap REST API |
| **Icons** | @mui/icons-material |
| **Environment** | Vite (import.meta.env) |

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v16+)
- Free API key from [openweathermap.org](https://openweathermap.org)

### Installation

1. **Clone the repository**
```bash
   git clone https://github.com/Shubham-kumar0001/react-weather-app.git
   cd react-weather-app
```

2. **Install dependencies**
```bash
   npm install
```

3. **Set up environment variables**

   Create a `.env` file in the root directory:
```env
   VITE_API_KEY=your_openweathermap_api_key
```

4. **Start the app**
```bash
   npm run dev
```

5. Open `http://localhost:5173` in your browser 🎉

---

## 📁 Project Structure

```
react-weather-app/
│
├── src/
│   ├── WeatherApp.jsx    # Main parent component
│   ├── SearchBox.jsx     # Search input & API fetch logic
│   ├── SearchBox.css
│   ├── InfoBox.jsx       # Weather card with dynamic image
│   ├── InfoBox.css
│   ├── App.jsx           # Root component
│   └── main.jsx          # Entry point
├── .env                  # Not committed
├── .gitignore
├── index.html
├── package.json
└── vite.config.js
```

---

## 📸 Screenshots

### 🌤️ Hot Weather — Delhi
![Delhi](https://github.com/user-attachments/assets/0d7159b0-1137-4eaf-81fd-3a9e82ca5dc7)

### ❄️ Cold Weather — London
![London](https://github.com/user-attachments/assets/7d594a09-f7f7-492f-ac05-27e08f86d032)

### ⛈️ Rainy Weather — Denmark
![Denmark](https://github.com/user-attachments/assets/dcdf8fda-e8f1-44a0-9f8b-c69f3a2cb133)

---

## 🧠 What I Learned

- Fetching and handling data from a **public REST API** using async/await
- Managing component state with **React useState** hook
- **Lifting state up** — passing data between parent and child components
- **Conditional rendering** based on API response values
- Using **Material UI** components — Card, CardMedia, TextField, Button, Icons
- **Environment variables** in Vite with `import.meta.env`
- **Error handling** in async functions using try/catch

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ by <a href="https://github.com/Shubham-kumar0001">Shubham Kumar</a></p>
