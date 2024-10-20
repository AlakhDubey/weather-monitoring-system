# Weather Monitoring System
 
## Description

A real-time data processing application that monitors and analyzes weather conditions across major Indian metros using the OpenWeatherMap API. The system retrieves current weather data, calculates daily summaries, and alerts users based on configurable thresholds, providing insights into temperature and weather conditions.

## Features

- **Real-Time Data Retrieval**: Continuously fetches weather data from the OpenWeatherMap API for major metros in India.
- **Temperature Conversion**: Converts temperatures from Kelvin to Celsius or Fahrenheit based on user preference.
- **Daily Summaries**: Aggregates weather data to provide daily summaries, including average, maximum, and minimum temperatures, as well as the dominant weather condition.
- **Alerting System**: Configurable thresholds for temperature and weather conditions, with alerts sent via email or console output.
- **Visualizations**: (To be implemented) A dashboard to visualize daily summaries and alerts.

## Technologies Used

- **Node.js**: For the server-side application.
- **Express**: Web framework for Node.js.
- **Axios**: For making API requests.
- **Mongoose**: MongoDB object modeling tool.
- **Nodemailer**: For sending email alerts.
- **MongoDB**: Database for storing weather data and summaries.

## Getting Started

### Prerequisites

- Node.js installed on your machine.
- MongoDB setup (either locally or using a service like MongoDB Atlas).
- An OpenWeatherMap API key.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-monitoring-system.git
   cd weather-monitoring-system
   
2.Install dependencies:

bash
npm install

3.Create a .env file with your OpenWeatherMap API key and MongoDB connection string:

plaintext
OPENWEATHER_API_KEY=your_openweather_api_key
MONGODB_URI=your_mongodb_connection_string
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password

**Running the Application
**
To start the server, run:

bash
Copy code
node src/server.js

**Running Tests
**
You can run tests using:

bash
npm test

**License**
This project is licensed under the MIT License - see the LICENSE file for details.

**Acknowledgments
**
OpenWeatherMap API for providing the weather data.
Node.js for the server-side environment.
