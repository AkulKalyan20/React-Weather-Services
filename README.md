# Weather Dashboard

A modern, responsive weather application built with React, TypeScript, and Chart.js. Get current weather conditions, 24-hour forecasts, and historical weather data with beautiful visualizations.

## Features

- 🌡️ Current weather conditions with detailed metrics
- 📊 24-hour forecast with temperature and humidity charts
- 📈 Historical weather data visualization
- 🔍 Search for any city worldwide
- 📱 Fully responsive design that works on all devices
- 🌙 Dark mode support (coming soon)

## Prerequisites

- Node.js (v14 or higher)
- npm (v7 or higher) or yarn
- An OpenWeatherMap API key (free tier available)

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/weather-dashboard.git
   cd weather-dashboard
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory and add your OpenWeatherMap API key:
   ```
   REACT_APP_OPENWEATHER_API_KEY=your_api_key_here
   ```

4. **Start the development server**
   ```bash
   npm start
   # or
   yarn start
   ```
   The app will be available at `http://localhost:3000`

## Available Scripts

- `npm start` - Start the development server
- `npm test` - Run tests
- `npm run build` - Build the app for production
- `npm run eject` - Eject from create-react-app (irreversible!)

## Technologies Used

- React 18
- TypeScript
- Chart.js & react-chartjs-2
- Axios for API requests
- date-fns for date manipulation
- React Icons
- CSS Modules for styling

## API Usage

This application uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch weather data. You'll need to sign up for a free API key.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for providing the weather data API
- [Chart.js](https://www.chartjs.org/) for beautiful data visualization
- [Create React App](https://create-react-app.dev/) for the project setup
