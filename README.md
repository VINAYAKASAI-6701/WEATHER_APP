# Weather App

## Overview
The Weather App is a web application built using Django that allows users to search for weather details based on a city. The app fetches real-time weather data using the OpenWeather API and displays important weather information such as temperature, humidity, pressure, and coordinates.

## Features
- **City Search:** Users can search for the weather of a specific city.
- **Weather Information:** The app displays the following weather details:
  - Country Code
  - Coordinates (Latitude and Longitude)
  - Temperature (in Kelvin)
  - Pressure (in hPa)
  - Humidity (in percentage)
- **Real-time Data:** The app fetches real-time weather data from the OpenWeather API.

## Tech Stack
- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, Bootstrap
- **API:** OpenWeather API

## Setup Instructions

### Prerequisites
- Python 3.x
- Django
- Internet connection (to fetch weather data from OpenWeather API)

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/VINAYAKASAI-6701/WEATHER_APP.git
   cd WEATHER_APP
Install the required Python packages:

bash
Copy
Edit
pip install -r requirements.txt
Set up the OpenWeather API key:

Go to OpenWeather and create an account to get an API key.

Replace the API key in views.py with your own API key.

Run the Django development server:

bash
Copy
Edit
python manage.py runserver
Contributing
Feel free to fork the repository, make changes, and create pull requests if you want to contribute. For any bugs or issues, please raise an issue on GitHub.
