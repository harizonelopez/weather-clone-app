"""
# Weather Clone App

## Introduction

The Weather Clone App is a simple yet powerful application that allows users to get the current weather information for any city or metropolitan area by entering the city name. It provides a description of the weather and the current temperature in Celsius.

## Features

- **Current Weather Information**: Get the latest weather description and temperature for any city.
- **Easy to Use**: Simple graphical user interface for entering city names and displaying results.
- **Contact Information**: Access links to the developer's GitHub, LinkedIn, and email.

## Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/weather-clone-app.git
    ```
2. **Navigate to the project directory**:
    ```sh
    cd weather-clone-app
    ```
3. **Install required libraries**:
    ```sh
    pip install requests tkinter pystray Pillow
    ```

## Usage

1. **Run the application**:
    ```sh
    python app.py
    ```
2. **Enter a city name**:
    - In the input field, type the name of the city for which you want to get the weather information.
      
3. **Get weather information**:
    - Click on the "click here" button to retrieve and display the weather information.
      
4. **Close the application**:
    - Click the "Close" button to exit the application.

## API Key

The application uses the OpenWeatherMap API to fetch weather data. Ensure you have a valid API key. Replace the placeholder API key in the `app.py` file with your own API key:
```python
api_key = 'your_openweathermap_api_key'
