# "Institute" Augmented Reality Application
The "Institute" AR application is designed to provide real-time information about ongoing classes within an institute's lobby area based on geolocation data. Upon entering the designated area, users can view text notifications indicating whether a class is currently in session and the remaining time until it concludes.

## System Requirements:
- A modern web browser with WebVR/WebXR support, such as Mozilla Firefox or Google Chrome.
- A smartphone or computer with a webcam and geolocation capabilities.

## Installation Instructions:
- Clone the repository or download the project files to your local machine or web server.
= Ensure your server is configured to serve A-Frame content and handle geolocation data securely.

## Usage:
1. Open the application in a supported web browser.
2. The application will request access to your location. Please allow it to enable the AR features.
3. The AR view will display a text overlay within the lobby coordinates, providing information on current classes and their duration.
4. If no class is in session, it will indicate that the space is currently available.

## Features:
- **Geolocation Tracking:** Uses the device's GPS to confirm the user's presence in the institute's lobby.
- **Real-time Class Status:** Provides live updates on whether classes are in session.
- **Class Countdown:** Displays the remaining time for the ongoing class session.
