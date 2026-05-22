# React Weather App 🌤️

A simple weather application built with **React** and **Material UI** that shows real-time weather data for any city using the OpenWeatherMap API.

## Features

- Search weather by city name
- Displays temperature, humidity, min/max temp, and feels-like
- Dynamic background image based on weather conditions (hot, cold, rainy)
- Weather condition icons (sunny, stormy, snowy)

## Tech Stack

- React (Vite)
- Material UI (MUI)
- OpenWeatherMap API

## Getting Started

### Prerequisites
- Node.js installed
- Free API key from [openweathermap.org](https://openweathermap.org)

### Installation

```bash
git clone https://github.com/YOUR_USERNAME/react-weather-app.git
cd react-weather-app
npm install
```

### Setup

Replace the `API_KEY` in `src/SearchBox.jsx` with your own OpenWeatherMap key:

```js
const API_KEY = "your_api_key_here";
```

### Run

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

## Screenshots

![Weather App Screenshot](./screenshot.png)

## License

MIT
