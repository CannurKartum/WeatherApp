#Weather App with MVI Clean Architecture using Jetpack Compose 

Welcome to the Weather App project! This app is built using the Model-View-Intent (MVI) pattern and follows clean architecture principles. It leverages Jetpack Compose for the UI and the OpenWeather API for weather data.

##Features

MVI Architecture: Ensures unidirectional data flow and easy state management.
Jetpack Compose: Modern toolkit for building native Android UIs.
OpenWeather API: Fetches real-time weather data.
Clean Architecture: Separates concerns with well-defined layers.

##Project Structure

data: Contains data sources, repositories, and models.
domain: Contains use cases and domain models.
presentation: Contains the UI layer (Jetpack Compose) and ViewModels.


##Key Classes
WeatherViewModel: Handles the business logic and state management.
WeatherRepository: Fetches weather data from the API.
WeatherScreen: Composable function displaying weather information.

##Usage
Home Screen: Displays current weather information based on the user's location.
Search Functionality: Allows users to search for weather in different cities.
Settings: Customize units and other preferences.


For more details, watch the full tutorial on [Youtube](https://www.youtube.com/watch?v=eAbKK7JNxCE) and follow along with the step-by-step guide​
