[README.md](https://github.com/user-attachments/files/28850715/README.md)
# Glass Weather App 🌤️

This is a small project I built to practice frontend design — a glassmorphism style weather app with a map-style background, frosted glass cards, and a floating GPS button that detects your location automatically.

I wanted something that looked modern and "trendy" (lots of blur effects, transparency, soft gradients) instead of the usual flat weather UI.

## What it has

- Glassmorphism design (frosted blur cards over a gradient background)
- Map-grid style background for that "tracking" feel
- Floating GPS button — tap it and it grabs your current location using the browser's Geolocation API
- A small hourly forecast strip
- World clock section showing time in New York, London, Dubai, Tokyo and Sydney
- Works on mobile and desktop, single HTML file, nothing to install

## Live site

https://theanasnadeem5.github.io/weather-app/

## Running it locally

Just download `index.html` and open it in your browser. That's it, no setup needed.

## How I built it

Pure HTML, CSS and JavaScript — no frameworks. Icons are from Tabler Icons (loaded via CDN). Location detection uses `navigator.geolocation`.

## Note on weather data

Right now the weather numbers (temperature, humidity, wind etc.) are randomly generated for demo purposes — I haven't connected a real weather API yet. Planning to hook it up to OpenWeatherMap later using the lat/long from the GPS button.

## To-do / ideas for later

- [ ] Connect real weather API
- [ ] Add more cities to world clock
- [ ] Add dark/light theme toggle
- [ ] Animate weather icons based on condition

---
Made by [theanasnadeem5](https://github.com/theanasnadeem5)
