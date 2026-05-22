🌤️ React Weather App

A React weather application that fetches real-time data from OpenWeatherMap API and displays temperature, humidity, and weather conditions with dynamic imagery.

Show Image
Show Image
Show Image
Show Image
Show Image
Show Image

✨ Features

🔍 Search Weather — Search real-time weather by any city name
🌡️ Weather Details — Temperature, humidity, min/max temp and feels-like
🖼️ Dynamic Background — Background image changes based on weather (hot, cold, rainy)
⛅ Weather Icons — Sunny, Thunderstorm, Snowflake icons from MUI
❌ Error Handling — Shows "No such place exists!" for invalid cities
📱 Responsive Design — Clean card layout using Material UI


🛠️ Tech Stack
LayerTechnologyFrontend FrameworkReact (Vite)UI LibraryMaterial UI (MUI v5)LanguageJavaScript (ES6+)StylingCSS3APIOpenWeatherMap REST APIIcons@mui/icons-materialEnvironmentVite (import.meta.env)

🚀 Getting Started
Prerequisites

Node.js (v16+)
Free API key from openweathermap.org

Installation

Clone the repository

bash   git clone https://github.com/YOUR_USERNAME/react-weather-app.git
   cd react-weather-app

Install dependencies

bash   npm install

Set up environment variables
Create a .env file in the root directory:

env   VITE_API_KEY=your_openweathermap_api_key

Start the app

bash   npm run dev

Open http://localhost:5173 in your browser 🎉


📁 Project Structure
react-weather-app/
│
├── src/
│   ├── WeatherApp.jsx    # Main parent component, holds state
│   ├── SearchBox.jsx     # Search input & API fetch logic
│   ├── SearchBox.css
│   ├── InfoBox.jsx       # Weather card with dynamic image & icons
│   ├── InfoBox.css
│   ├── App.jsx           # Root component
│   └── main.jsx          # ReactDOM entry point
├── public/
├── .env                  # Environment variables (not committed)
├── .gitignore
├── index.html
├── package.json
└── vite.config.js

📸 Screenshots
🌤️ Hot Weather — Delhi
<img width="715" height="881" alt="Delhi" src="https://github.com/user-attachments/assets/0d7159b0-1137-4eaf-81fd-3a9e82ca5dc7" />
❄️ Cold Weather — London
<img width="589" height="840" alt="London" src="https://github.com/user-attachments/assets/7d594a09-f7f7-492f-ac05-27e08f86d032" />
⛈️ Rainy Weather — Denmark
<img width="559" height="854" alt="Denmark" src="https://github.com/user-attachments/assets/dcdf8fda-e8f1-44a0-9f8b-c69f3a2cb133" />

🧠 What I Learned

Fetching and handling data from a public REST API using async/await
Managing component state with React useState hook
Lifting state up — passing data between parent and child components
Conditional rendering based on API response values
Using Material UI components — Card, CardMedia, TextField, Button, Icons
Environment variables in Vite with import.meta.env
Error handling in async functions using try/catch
Dynamic UI updates based on real weather data


🤝 Contributing
Contributions, issues and feature requests are welcome!

Fork the project
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request


📄 License
This project is licensed under the MIT License.

<p align="center">Made with ❤️ by <a href="https://github.com/Shubham-kumar0001">Shubham Kumar</a></p>
