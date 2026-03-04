# Weather Dashboard Application

## Overview
The Weather Dashboard is a web application that provides users with up-to-date weather information from various locations.

## Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/chuang910803-ship-it/6437979.git
   cd 6437979
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Get an API key:**
   - Sign up at [OpenWeatherMap](https://openweathermap.org) to get your API key.
   - Add your API key to a `.env` file in the root directory of the project:
     ```env
     API_KEY=your_api_key_here
     ```

## Usage Instructions
1. **Start the application:**
   ```bash
   npm start
   ```
2. **Access the dashboard:**
   Open your web browser and go to `http://localhost:3000`.

## API Key Instructions
- Ensure you replace `your_api_key_here` with the actual API key obtained from OpenWeatherMap.
- The API key is necessary for the application to function correctly as it fetches weather data from the API.