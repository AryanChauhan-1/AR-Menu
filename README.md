# AR-Menu
AR powered Immersive Menu UI transforming traditional menu designs.

A cinematic, mobile-first digital menu built for restaurants. Customers scan a single QR code and land on an immersive 3D menu where they can browse dishes, view them in augmented reality, and see full dish details — all without downloading an app.
What it is
A single HTML file that replaces the traditional paper or PDF menu. Each dish has a 3D model that the customer can rotate with touch. Tapping "View on your table" places the dish in the real world using the phone's AR — Android uses Google Scene Viewer, iOS uses QuickLook.
Why it's built this way
One file means one deployment. No backend, no database, no framework. The entire menu — all dishes, categories, prices, descriptions — lives in a single JavaScript object inside the HTML. Updating a price or adding a dish is one line of text.
Hosting on Netlify with GitHub means every change pushed to the repo goes live automatically in under a minute.
