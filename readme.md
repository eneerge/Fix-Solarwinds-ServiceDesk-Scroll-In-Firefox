# Scrolling Fix for ServiceDesk
Solarwinds attaches a "wheel" javascript event to the dropdown div which breaks Firefox's scrolling (doesn't affect Chromium based browser). It scrolls to the bottom of the div, skipping most options.

<img width="647" alt="event" src="https://github.com/eneerge/Fix-Solarwinds-ServiceDesk-Scroll-In-Firefox/assets/7434613/999952e7-e2bf-4916-bc9e-122d48b5a1a3">

<img width="647" alt="event" src="https://github.com/eneerge/Fix-Solarwinds-ServiceDesk-Scroll-In-Firefox/assets/7434613/4c0ac891-7755-45ab-8511-f39c13adf2ce">




This is a uBlock defuser that will remove that Javascript event from running on the page, fixing the issue.

<img width="534" alt="thefix" src="https://github.com/eneerge/Fix-Solarwinds-ServiceDesk-Scroll-In-Firefox/assets/7434613/f2a9f3d1-dee9-453d-b64c-9a97094fff52">
<img width="534" alt="thefix" src="https://github.com/eneerge/Fix-Solarwinds-ServiceDesk-Scroll-In-Firefox/assets/7434613/6a9a19e6-230c-4bee-a023-67eace68c81d">



