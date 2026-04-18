# Weather Report Automation
An n8n automation workflow that fetches real-time weather data for Accra, Ghana using OpenWeatherMap API, generates a friendly morning weather report using Google Gemini AI and delivers it via email every morning at 7AM.

## How It Works
1. Schedule trigger fires every morning at 7AM
2. HTTP Request fetches live weather data from OpenWeatherMap
3. Code node formats and extracts relevant weather fields
4. Google Gemini generates a friendly weather summary
5. Gmail sends the report to your email

## Tools & Stack
- **n8n** — Workflow automation
- **OpenWeatherMap API** — Live weather data
- **Google Gemini** — AI weather summary
- **Gmail OAuth2** — Email delivery

## Setup
- n8n self-hosted via Docker
- OpenWeatherMap free API key required
- Gmail OAuth2 credentials required
- Google Gemini API key required

## Sample Output
Good morning Accra! ☀️ It's a beautiful clear sky day with a temperature of 27°C, though it feels like 31°C outside. Humidity is high at 83% so stay hydrated! Wind is light at 3 m/s. Perfect day to carry a light outfit and sunscreen. Have a great day! 🌤️

## Author
**Dan Nyarkoh Andoh (DNA)** — Data & AI Automation Engineer
- GitHub: github.com/99-dn
- LinkedIn: https://www.linkedin.com/in/dan-nyarkoh-andoh-313a383b2
