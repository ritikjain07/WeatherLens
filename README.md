# WeatherLens - README

## Overview
**WeatherLens** is a dynamic weather forecast application built using PHP, JavaScript, and the Weather API. It provides accurate weather information for any location, featuring current conditions, a three-day forecast, and real-time weather alerts. The app uses **Tailwind CSS** for responsive styling.

![WeatherLens](images/Screenshot%20(977).png)
---

## Features
1. **Search by Location**  
   - Fetch detailed weather data for any city or region.  
2. **Real-Time Weather Details**  
   - Current temperature, humidity, wind speed, and more.  
3. **Three-Day Forecast**  
   - Daily high/low temperatures, sunrise/sunset, and chance of rain.  
4. **Weather Alerts**  
   - Displays active alerts like severe weather warnings.  
5. **Geolocation Support**  
   - Automatically fetches weather data for the user's current location.  
6. **Responsive Design**  
   - Fully responsive UI using **Tailwind CSS**.  

---

## Requirements
1. **XAMPP** or any local server environment with PHP support.  
   - Download XAMPP: [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html)  
2. **Weather API Key**  
   - Sign up at [WeatherAPI.com](https://www.weatherapi.com/) and get your API key.

---

## Setup Instructions
1. **Install XAMPP**  
   - Download and install XAMPP from the official website.  

2. **Clone or Download the Project**  
   - Clone this repository or download the files.  
   ```bash
   git clone https://github.com/ritikjain07/WeatherLens.git
   ```

3. **Move Project to XAMPP Directory**  
   - Place the project folder in the `htdocs` directory of your XAMPP installation.  
   ```plaintext
   Example: C:/xampp/htdocs/weatherlens
   ```

4. **Start XAMPP Services**  
   - Open the XAMPP Control Panel.  
   - Start **Apache** and **MySQL** services.  

5. **Update API Key**  
   - Replace the placeholder API key in the script section of `index.php` with your Weather API key:
   ```php
   const apiKey = 'your_api_key_here';
   ```

6. **Access the Application**  
   - Open a web browser and navigate to:
   ```plaintext
   http://localhost/weatherlens
   ```

---

## Usage
1. **Search Weather by Location**  
   - Enter a city or region in the search bar.  
   - Click "Get Weather" to display the current and forecast weather.  
2. **Use Geolocation**  
   - Allow the browser to access your location to view weather data automatically.  

---

## Known Issues
1. **API Limits**: Ensure your Weather API subscription covers enough requests.  
2. **Geolocation Access**: If the user denies access to location data, the app falls back to manual input.  

---

## Customization
- **Styling**: Modify the UI by editing `Tailwind CSS` classes in the `index.php` file.  
- **Features**: Add more data like hourly forecasts or air quality from the Weather API.  

---

## Future Enhancements
- Integrate hourly forecasts.  
- Add air quality index (AQI) and precipitation maps.  
- Create a dark mode for the UI.  

---
## **Contact**  
For queries or feedback, feel free to contact me:  
**Ritik Jain**  
📧 Email: [ritikjain4560@gmail.com](mailto:ritikjain4560@gmail.com)  
📍 GitHub: [ritikjain07](https://github.com/ritikjain07)  
---
Enjoy using **WeatherLens – Focus on the Forecast!** 😊
