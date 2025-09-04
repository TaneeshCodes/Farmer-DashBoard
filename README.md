Farmer Dashboard 🚜
A single-file, frontend-only web application for monitoring farm plots. This dashboard is built with vanilla HTML, CSS, and JavaScript, with no external frameworks or dependencies. It is fully responsive, works offline, and demonstrates a modern UI with dynamic, stateful components.

✨ Features
Single-File Application: The entire app is contained within a single index.html file.

Zero Dependencies: Built purely with vanilla HTML5, CSS3, and modern JavaScript (ES6+). No frameworks, libraries, or CDNs.

Fully Responsive: The layout seamlessly adapts from desktop to tablet and mobile screens.

Offline Functionality: Works perfectly when opened directly from the local file system without needing a web server.

Mock Login: A simple login screen to simulate user entry.

Interactive Dashboard:

Stats Overview: At-a-glance cards for average moisture, active sprays, and plot health.

Plot Grid: A responsive grid displaying individual farm plots with key data (crop, moisture, health).

Live Data Simulation: Plot data (moisture) updates every 10 seconds to simulate a real-time feed.

Search & Filter: Instantly filter plots by crop name.

Detailed Plot Modal:

Click any plot to view detailed information in a modal.

Canvas Chart: A mini-chart visualizes historical moisture data, rendered with the HTML <canvas> API.

Interactive Notes: Add and view notes for each plot.

State Persistence: User actions like toggling sprays, completing tasks, and adding notes are saved to the browser's localStorage and persist across sessions.

Task Management: A sidebar lists daily tasks that can be marked as complete.
