# Klimate: Weather Web Application

<img width="1022" alt="{5D896A5D-C9AC-4A48-8F0E-D8106E0B05DC}" src="https://github.com/user-attachments/assets/269460b0-f8b2-4765-a707-497d2b6dd94b" />

## 🌟 Overview

Klimate is a sleek and user-friendly weather web application that provides real-time weather data for any location. The application features current weather conditions, a detailed hourly temperature chart, a 5-day forecast, and additional weather details such as humidity, wind speed, and sunrise/sunset timings. 

This project leverages modern web development technologies to ensure responsiveness, performance, and a great user experience.

## 🚀 Features

- **Real-Time Weather Data**: Displays temperature, humidity, wind speed, and weather conditions for any location.
- **Hourly Temperature Graph**: Visualize temperature trends throughout the day using dynamic charts.
- **5-Day Weather Forecast**: View upcoming weather conditions for better planning.
- **Responsive Design**: Optimized for desktops and mobile devices.
- **Dark Mode**: Easy on the eyes with a beautifully crafted dark UI.
- **Search Functionality**: Search for weather information for any city.
- **Auto Location Detection**: Displays the weather of your current location by default.

## 🛠 Tech Stack

### Frontend:
- **React**: For building the user interface and managing components.
- **TypeScript**: Ensures type safety and reduces runtime errors.
- **Tailwind CSS**: For fast and responsive styling.
- **Shadcn**: For elegant and reusable UI components.

### State Management:
- **TanStack Query**: For efficient data fetching and state synchronization.

### Data Visualization:
- **Recharts**: For rendering interactive and responsive charts.


## 📦 Installation

Follow these steps to set up and run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/Pixel-20/Klimate-Weather-Web-Application.git
   cd Klimate-Weather-Web-Application
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your OpenWeather API key:
   ```env
   REACT_APP_WEATHER_API_KEY=your_api_key_here
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:5173`.


## 🔗 API Used

- [OpenWeather API](https://openweathermap.org/api): For fetching real-time weather data.



