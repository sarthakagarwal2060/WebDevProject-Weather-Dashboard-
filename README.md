# Weather Dashboard

The Weather Dashboard is a web application that provides users with real-time weather updates and a 4-day forecast for any city they enter. It utilizes the OpenWeather API to fetch weather data and displays it in a user-friendly format.

## Features

### 1. Search for Weather
- Enter a city name in the input field to fetch weather data.
- Displays an error message if the input is empty or invalid.

### 2. Current Weather
- Displays the following details for the selected city:
  - Temperature
  - Max/Min Temperature
  - Wind Speed
  - Humidity
  - Weather Condition

### 3. 4-Day Forecast
- Provides a forecast for the next 4 days, including:
  - Max/Min Temperature
  - Wind Speed
  - Humidity

### 4. Responsive Design
- Designed to work on various devices with an intuitive and visually appealing layout.

### 5. Error Handling
- Handles invalid input and API errors gracefully, displaying appropriate messages to the user.

## Technologies Used

### Frontend
- **HTML**: Structure of the webpage.
- **CSS**: Styling for the dashboard.
- **JavaScript**: Interactivity and API integration.

### API
- [OpenWeather API](https://openweathermap.org/): Provides weather data for the application.

## How to Run

1. Clone the repository or download the files.

   ```bash
   git clone https://github.com/your-repo/weather-dashboard.git
   ```

2. Open the `index.html` file in your web browser.

3. Enter a city name in the search bar and click the "Search" button to fetch weather data.

## Project Structure

```plaintext
├── index.html        # Main HTML file
├── styles.css        # Inline CSS (within the HTML file in this case)
├── script.js         # JavaScript code for functionality
```

## API Key Configuration
The application uses a default API key for OpenWeather. To use your own API key:
1. Sign up at [OpenWeather](https://openweathermap.org/) to get your API key.
2. Replace the value of the `apiKey` variable in the `<script>` section of `index.html`:

   ```javascript
   const apiKey = "your_api_key_here";
   ```

## Netlify Deployment

To deploy the Weather Dashboard using Netlify:
1. Log in to your [Netlify](https://www.netlify.com/) account.
2. Drag and drop the project folder into the Netlify dashboard or link your GitHub repository.
3. Copy the generated Netlify URL after deployment.
4. Replace the placeholder text below with your Netlify link:

   **Live Demo:** [Weather Dashboard on Netlify]([https://your-netlify-link.netlify.app](https://gleeful-paletas-79f9d0.netlify.app/))

## Demo
You can view the application in action by opening the `index.html` file in any modern web browser.

## Future Improvements
- Add support for geolocation to fetch weather data for the user's current location.
- Implement a loading indicator while fetching data.
- Improve error handling for cities with duplicate names.
- Enhance the UI/UX with advanced styling frameworks like Bootstrap or Tailwind CSS.

## License
This project is open-source and available under the MIT License. Feel free to use, modify, and distribute it as needed.

---

Feel free to contribute to this project by submitting issues or pull requests!

