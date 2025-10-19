# The Summoning Countdown

This repository hosts a richly themed single-page countdown experience for "The Summoning" event. It showcases dynamic styling, atmospheric animations, and synchronized clocks for Belgrade and Singapore so visitors can track the ritual across time zones.

## Viewing the page

Open `index.html` in any modern browser. No build step is required—the HTML file bundles the styles and scripts that power the countdown, visual effects, and time synchronization logic.

If you prefer to launch a lightweight local server (for example, to mimic a production hosting environment), run `python3 -m http.server` from the repository root and visit http://localhost:8000/ in your browser.

## Development notes

The page relies on the World Time API to synchronize the local countdown with UTC. If the API is unreachable (particularly on mobile devices), it gracefully falls back to device time while notifying the user. Animations and particle effects are tuned for both desktop and mobile experiences, with additional accessibility considerations such as reduced motion support.
