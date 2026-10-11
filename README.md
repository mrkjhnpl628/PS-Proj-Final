# ShieldBot - Platform Security Academy

Front-end e-learning website (HTML, CSS, JavaScript). Keep all files and the `images/` folder together, then double-click `index.html`.

## Features
Sign up / log in (with confirm password), 8 courses and 23 topics, quizzes (75% to pass) that unlock the next topic, 15 badges, profile with display name and icon upload, Video library (links open on YouTube in a new tab), dark mode, mobile menu.

## Files
index.html, style.css, courses.js (content), resources.js (images, video links, learn-more links), script.js (app), images/.

## Add a video
In `resources.js` add the YouTube ID (the part after `v=`) to `VIDEOS`, then list it in a topic's `v:[...]`.

## Limitations
Front-end demo: accounts and progress are stored in the browser, so a determined user could edit them. Real enforcement needs a backend. Google sign-in is shown as unavailable.
