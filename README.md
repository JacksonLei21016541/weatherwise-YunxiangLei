# WeatherWise Project

## Project Overview

The **WeatherWise** project is a weather application designed to provide users with a simple yet powerful way to check weather information. As a beginner in programming, I created this project to learn how to build a functional app while leveraging AI tools for assistance. The goal was to develop an application that allows users to:

- Check the current weather for a specified city.
- View weather forecasts for up to 5 days.
- Visualize temperature trends and precipitation probability through charts.
- Ask natural language questions like "Will it rain tomorrow?" and receive answers.

The application combines a user-friendly interface with a conversational chatbot, following a hybrid approach that caters to both visual and text-based users. Key features include:

- **Current Weather Display**: Shows temperature, condition, humidity, wind speed, and more.
- **Weather Forecast**: Displays a 5-day forecast with max/min temperatures, conditions, and rain chances.
- **Data Visualization**: Includes temperature trend charts (line graph) and precipitation probability charts (bar graph).
- **Natural Language Queries**: Users can ask weather-related questions, such as "Will it rain tomorrow in Sydney?"
- **Extensions** (added enhancements):
  - **Weather Alerts**: Warns users of extreme conditions like heavy rain or high temperatures.
  - **Customizable Units**: Allows switching between metric (Celsius, km/h) and imperial (Fahrenheit, mph) units.
  - **Custom Weather Insights**: Provides personalized suggestions, e.g., "It's a great day for outdoor activities!"

I used two AI tools to assist in development: **ChatGPT** for project management and translation support, and **Grok** (by xAI) as the primary tool for coding, debugging, and providing suggestions. The project was built in **Google Colab**, using Python libraries like `fetch-my-weather` for weather data, `pyinputplus` for user input, and rule-based parsing for natural language queries.

## Setup Instructions

To run the WeatherWise project, follow these steps to set up the environment and execute the code. The project is designed to run in **Google Colab**, a free cloud-based Jupyter Notebook environment.

### Prerequisites
- A web browser with internet access.
- A Google account to use Google Colab.
- Basic knowledge of Python (helpful but not required).

### Step 1: Open the Project in Google Colab
1. Download the `WeatherWise_MyProject (Extensions).ipynb` file from the GitHub repository.
2. Go to [Google Colab](https://colab.research.google.com/).
3. Click **File** > **Upload Notebook**.
4. Upload the `WeatherWise_MyProject (Extensions).ipynb` file.
5. The notebook will open in Google Colab, ready for execution.

### Step 2: Install Required Tools
The project relies on three Python libraries: `fetch-my-weather`, `hands-on-ai`, and `pyinputplus`. These are installed in the first code cell of the notebook. Follow these steps:

1. Run the first code cell in the notebook, which contains:
   ```python
   # Install the required tools
   !pip install fetch-my-weather
   !pip install hands-on-ai
   !pip install pyinputplus
