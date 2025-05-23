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

2. Wait for the installation to complete. You’ll see output messages confirming that the packages are installed.

### Step 3: Run the Code
1. Run the subsequent code cells in order. Each cell contains a part of the program:
   - **Imports**: Imports necessary libraries (`os`, `time`, `fetch_my_weather`, `hands_on_ai`, `pyinputplus`).
   - **Functions**: Defines functions like `get_weather_data()`, `display_welcome()`, `parse_weather_question()`, etc.
   - **Main Program**: The `main()` function runs the application.
2. The final cell (`if __name__ == "__main__": main()`) starts the application.
3. Follow the prompts in the output:
   - Enter a city name (e.g., "Sydney").
   - Choose options from the menu (e.g., view current weather, forecast, charts, ask a question, change units, or exit).

### Step 4: Interact with the Application
Input a City: Enter a city name when prompted (e.g., "Sydney").
Navigate the Menu: Use the numbered menu to select options like viewing the current weather, forecast, or charts.
Ask Questions: Select the "Ask a Weather Question" option and type questions like "Will it rain tomorrow?"
Change Units: Switch between metric and imperial units using the "Change Units" option.
View Alerts and Insights: The dashboard will show weather alerts (e.g., heavy rain warnings) and personalized insights (e.g., "Consider indoor activities today").
Troubleshooting
Invalid City Name: If the city name is invalid, the app will prompt you to try again. Use the format "City, Country" (e.g., "Sydney, Australia") for best results.
No Internet: Ensure you have a stable internet connection, as the app fetches weather data online.
Errors in Colab: If you encounter errors, restart the runtime (Runtime > Restart runtime) and rerun all cells.
