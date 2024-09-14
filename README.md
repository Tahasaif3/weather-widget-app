# Weather Widget

A modern and responsive weather widget application built with Next.js and TypeScript. This widget allows users to search for weather information based on their city, view current weather conditions, and toggle between Celsius and Fahrenheit units.

## Features

- **Weather Data Fetching**: Retrieves weather data using a weather API.
- **Responsive Design**: Adapts to various device sizes including mobile phones and laptops.
- **Dynamic Backgrounds**: Changes background gradients based on weather conditions.
- **Temperature Conversion**: Toggle between Celsius and Fahrenheit.
- **Error Handling**: Displays appropriate messages for invalid city inputs and other errors.

## Installation

To get started with the Weather Widget application, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/weather-widget.git
   cd weather-widget
   ```

2. **Install Dependencies**:
   Make sure you have Node.js installed. Then run:
   ```bash
   npm install
   ```

3. **Configure Environment Variables**:
   Create a `.env.local` file in the root directory of the project and add your API key:
   ```env
   API_KEY=your_weather_api_key
   ```

4. **Run the Development Server**:
   ```bash
   npm run dev
   ```
   Open `http://localhost:3000` in your browser to view the application.

## Usage

1. **Search for Weather**: Enter a city name in the input box and click "Get Weather" to fetch the current weather data.
2. **Toggle Units**: Click the "Convert to Fahrenheit" or "Convert to Celsius" button to switch between temperature units.
3. **View Weather Information**: See the weather description, temperature, feels like, humidity, pressure, and wind speed.

## Folder Structure

- **app/**: Contains the main application code.
  - **api/**: Contains API routes for fetching weather data.
    - **weather/**: Weather-related API route.
    - **env-test/**:  environment test route.
  - **components/**: Reusable UI components (e.g., Button, Card, Input).
  - **fonts/**: Custom fonts used in the application.
  - **lib/**: Utility functions and helpers.
  - **weather-widget/**: Main page for the weather widget.

- **.env.local**: Contains your environment variables.

- **globals.css**: Global CSS styles applied to the application.

- **layout.tsx**: Root layout component that includes global styles and metadata.

- **pages.tsx**: Application entry point.

## Contributing

Feel free to contribute to the project by submitting issues or pull requests. For detailed instructions on contributing, please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or feedback, please reach out to me at [tahasaif454@gmail.com].
