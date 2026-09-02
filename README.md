# Weather Schedule

A simple single-file PWA that shows today’s hourly weather beside your Google Calendar events.

## Run locally

Serve the folder over `http://` or `https://` so geolocation and Google sign-in work:

```bash
python -m http.server 5500
```

Open <http://localhost:5500/weather-schedule.html> in your browser.

## Connect Google Calendar

1. Enable the Google Calendar API in the [Google Cloud Console](https://console.cloud.google.com/).
2. Create an OAuth client ID for a **Web application**.
3. Add `http://localhost:5500` as an authorized JavaScript origin.
4. Paste the client ID into `GOOGLE_CLIENT_ID` in `weather-schedule.html`.
5. Click **Connect calendar** in the app.

The app requests read-only calendar access. Weather data comes from Open-Meteo and does not require an API key.

## Location

Click **Set location** to use your current location or search for a city.
