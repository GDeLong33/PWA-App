# Weather Schedule

[Open Weather Schedule](https://gdelong33.github.io/PWA-App/)

Weather Schedule is a single-file progressive web app that displays today’s weather beside your Google Calendar events, hour by hour.

## Features

- Hourly weather from [Open-Meteo](https://open-meteo.com/)
- Weather based on browser geolocation or a manually entered city
- Read-only Google Calendar integration
- Events displayed across every hour they overlap
  - For example, a 10:00 AM–1:00 PM event appears at 10 AM, 11 AM, and 12 PM
- Responsive layout for desktop and mobile browsers
- Can be added to a phone’s home screen

## Using The App

1. Open the [Weather Schedule page](https://gdelong33.github.io/PWA-App/).
2. Allow location access, or choose **Set location** and enter a city.
3. Select **Connect calendar**.
4. Sign in with an approved Google account.
5. Allow read-only calendar access.

## Google Calendar Setup

The app uses Google OAuth and requests only:

```text
https://www.googleapis.com/auth/calendar.readonly