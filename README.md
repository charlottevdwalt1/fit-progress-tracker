# Stride — Training Planner

A mobile-friendly weekly agenda and workout tracker built with vanilla HTML, CSS, and JavaScript. No build step or external runtime dependencies are required.

## Run locally

Serve the repository directory using any static web server (service workers require localhost or HTTPS), then open the URL on your phone. For example:

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000` in a browser. To install it on a phone, use the browser's **Add to Home Screen** option over HTTPS.

## Features

- Repeating Monday–Sunday training agenda with week navigation.
- Strength logging for weight and reps across every prescribed set; entries are saved by date so prior sessions can guide progressive overload.
- Wednesday and Saturday HIIT choice: the provided custom workout or a class with a name and notes.
- Run distance, duration, run type, pace calculation, session completion, and notes.
- Thursday Pilates/rest choice, plus completion tracking.
- Progress totals and local-device persistence via `localStorage`.
- Installable/offline app shell via the web app manifest and service worker.

All tracking is stored locally in the browser on the device; it is not synced between devices.
