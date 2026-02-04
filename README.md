# Online Timer

This project is a simple online timer application, created as a school assignment using JavaScript.

## Features

*   **User Authentication:** Users can register and log in to their accounts.
*   **Timer Management:**
    *   Create custom timers with names and durations (hours, minutes, seconds).
    *   Start, stop, pause, and resume timers.
    *   Delete timers.
*   **Dashboard:** A personal dashboard to view and manage all your timers.
*   **Real-time Updates:** The dashboard updates in real-time without needing to reload the page.
*   **Dark Mode:** Switch between light and dark themes for comfortable viewing.
*   **Fullscreen Mode:** View a timer in fullscreen for better focus.
*   **Responsive Design:** The application is designed to work on different screen sizes.

## Tech Stack

*   **Frontend:** HTML, CSS, JavaScript
*   **Backend:** Node.js, Express.js
*   **Data Storage:** A simple JSON file is used for data persistence.
*   **Authentication:** JWT (JSON Web Tokens) are used for authentication.
*   **Password Hashing:** `bcrypt` is used to hash user passwords.

## How to run
*   Install nodejs and npm
*   Run `npm install` to install all the dependencies
*   Run `node src/index.js` and the server will open on port 3000
