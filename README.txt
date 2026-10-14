VOICENIX STUDIOS — FIXED WEBSITE PROJECT

START HERE
1. Keep index.html, styles.css, script.js and the assets folder together.
2. Open index.html in a modern browser. No build step is required.
3. If you are using a local development server, run: python -m http.server 8000
   from this folder, then visit http://localhost:8000.

WHAT WAS FIXED
- The page content is visible by default, even if JavaScript is blocked or fails.
- Scroll animations only hide/reveal elements after the script has initialized correctly.
- The script includes a fail-open error handler so an interaction error does not blank the page.
- The navigation, copyright year and WhatsApp enquiry form are handled by script.js.

ASSETS AND CONTENT
- assets/weekend-offer-poster.jpg is the poster provided for this project.
- Other studio imagery is included in assets/ and stored locally.
- Portfolio titles are fictional demo concepts, not claims of actual client work. Replace them with approved credits before publishing.
- The enquiry form prepares a WhatsApp message for +91 98705 32587. It does not save submissions on a server.
- Confirm the contact number, address, discount terms and studio availability before publishing.
- Fonts load from Google Fonts when internet is available; fallback fonts are defined for offline use.
