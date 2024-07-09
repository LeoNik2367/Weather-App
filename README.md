# 🌦️ Weather App

Using the three building blocks of HTML, CSS, and JavaScript, this project demonstrates a functional weather application that fetches real-time weather data based on user input. It leverages asynchronous programming with API data and modern web-based functionalities.

## 🚀 Live Demo

Check out the live version of the app [MY WEATHER APP](https://weather-app-delta-neon.vercel.app)

## 🛠️ Tech Stack

- **HTML**: For the basic structure of the web pages.
- **CSS**: For styling and arranging content via CSS Flexbox.
- **JavaScript**: For DOM manipulation and asynchronous programming.
- **OpenWeatherMap API**: For fetching real-time weather data.

## 📚 Learnings

- **Asynchronous Programming**: Utilizing `fetch()` for API calls.
- **CSS Flexbox**: For arranging content responsively.
- **DOM Manipulation**: Using `document.getElementById()` to interact with and update the web page.

## 🚀 Deployment

This project is deployed on Vercel. Follow these steps to deploy your own version:

1. **Fork the Repository**: Click the fork button on the top right of the repository page to create a copy in your GitHub account.
2. **Clone the Repository**: 
    ```sh
    git clone https://github.com/your-username/Weather-App.git
    cd Weather-App
    ```
3. **Install Dependencies**: 
    ```sh
    npm install
    ```
4. **Set Up API Key**:
    - Create a `.env` file in the root directory.
    - Add your OpenWeatherMap API key:
      ```sh
      REACT_APP_WEATHER_API_KEY=your_api_key_here
      ```
5. **Deploy on Vercel**:
    - Create a new project on Vercel.
    - Import your GitHub repository.
    - Set the environment variable `REACT_APP_WEATHER_API_KEY` in the Vercel dashboard.
    - Deploy the project.

## 🔧 Further Improvements

- **Enhanced Error Handling**: Improve the user feedback for various error states.
- **UI Enhancements**: Make the UI more appealing and user-friendly.
- **Additional Features**: Add features like weekly forecasts, weather maps, etc.
- **Geolocation**: Automatically fetch weather data based on the user's current location.

## 🤝 Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue.
