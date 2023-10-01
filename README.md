# Weather-App
Weather App Python

Python Weather App

This is a simple Python application that fetches weather data from the OpenWeatherMap API based on the user's input (city name) and displays the weather information in a graphical user interface (GUI) created using the Tkinter library.

Prerequisites

Before running the application, make sure you have the following prerequisites installed:

- Python 3.x: You can download and install Python from the official Python website (https://www.python.org/downloads/).

Getting Started

1. Clone the Repository:

   git clone https://github.com/BarbaraKozlowska/weather-app.git

2. Navigate to the Project Directory:

   cd weather-app

3. Install Dependencies:

   Ensure you have the `requests` library installed. If not, you can install it using pip:

   pip install requests

4. Obtain an OpenWeatherMap API Key:

   To access weather data, you need to sign up for a free API key at OpenWeatherMap (https://openweathermap.org/) and replace "YOUR_API_KEY" in the code with your actual API key.

5. Run the Application:

   python weather_app.py

Usage

- Enter the name of the city for which you want to check the weather into the text entry field.
- Click the "Get Weather" button to fetch and display the weather information.
- The weather information will include the weather description, temperature (in Celsius), and humidity.

Troubleshooting

- If you encounter any issues with the app, ensure that your API key is correctly configured and that you have an active internet connection.
- The app may display "City not found" if the API does not have data for the entered city or if there are issues with the city name.

Contributing

Contributions are welcome! If you have ideas for improvements or additional features, feel free to open an issue or submit a pull request.


Acknowledgments

- This project was created as a learning exercise for Python programming and working with APIs.
