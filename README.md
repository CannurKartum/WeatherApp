
![Untitled design](https://github.com/CannurKartum/WeatherApp/assets/48458722/f7083bcb-6cbf-40d9-99db-33f66b4f9a7e)


# Weather App with MVI Clean Architecture using Jetpack Compose

This app is built using the Model-View-Intent (MVI) pattern and follows clean architecture principles. It leverages Jetpack Compose for the UI and the OpenWeather API for weather data.

## Features

- **MVI Architecture**: Ensures unidirectional data flow and easy state management.
- **Jetpack Compose**: Modern toolkit for building native Android UIs.
- **OpenWeather API**: Fetches real-time weather data.
- **Clean Architecture**: Separates concerns with well-defined layers.

## Project Structure

- **data**: Contains data sources, repositories, and models.
- **domain**: Contains use cases and domain models.
- **presentation**: Contains the UI layer (Jetpack Compose) and ViewModels.

### Key Classes

- **WeatherViewModel**: Handles the business logic and state management.
- **WeatherRepository**: Fetches weather data from the API.
- **WeatherScreen**: Composable function displaying weather information.

## Usage

1. **Home Screen**: Displays current weather information based on the user's location.
2. **Search Functionality**: Allows users to search for weather in different cities.
3. **Settings**: Customize units and other preferences.

---
## Acknowledgments

- Thanks to the creators of the tutorial for guiding through the MVI architecture and Jetpack Compose integration.
- Special thanks to [OpenWeather](https://openweathermap.org/) for providing the API.
---
For more details, watch the full tutorial on [YouTube](https://www.youtube.com/watch?v=eAbKK7JNxCE) and follow along with the step-by-step guide.
