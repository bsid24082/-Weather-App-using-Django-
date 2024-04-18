# -Weather-App-using-Django-
Lab 05. Build Weather App using Django framework



		

Here's a sample README file for your Django project:

---

# Weather App

## Overview
This Django project is a simple weather application that allows users to input a city name and retrieve weather information from the OpenWeatherMap API. It displays the current temperature, pressure, humidity, country code, and coordinates for the specified city. Additionally, it stores the retrieved weather data in the database for future reference.

## Features
- User-friendly interface for querying weather information
- Data storage in a database for historical weather data
- Integration with the OpenWeatherMap API for real-time weather updates

<img width="1440" alt="image" src="https://github.com/bsid24082/-Weather-App-using-Django-/assets/118895012/17d35781-306f-4732-8bf4-aae12f8c9340">

## Installation
1. Clone the repository to your local machine:
   ```
   git clone https://github.com/your-username/weather-app.git
   ```
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Obtain an API key from OpenWeatherMap by signing up on their website.
2. Replace the placeholder `'your_api_key_here'` in the `index` view function in `views.py` with your actual API key.
3. Run the Django development server:
   ```
   python manage.py runserver
   ```
4. Access the application in your web browser at `http://localhost:8000`.


<img width="1440" alt="image" src="https://github.com/bsid24082/-Weather-App-using-Django-/assets/118895012/c9f83230-6001-456f-b4db-a5646a23ac29">


## Configuration
- The application uses Django's built-in SQLite database by default. If you want to use a different database, you can modify the database settings in the `settings.py` file.
- Other configuration options, such as static files storage or debug mode, can also be adjusted in the `settings.py` file.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- This project utilizes the [OpenWeatherMap API](https://openweathermap.org/api) for weather data.
- Developed as part of a Django web development tutorial.

---

Feel free to customize this README according to your project's specific details and requirements.
