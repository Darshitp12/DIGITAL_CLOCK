# Real-Time Digital Clock

## Overview
This project is a stylish real-time digital clock that displays hours, minutes, and seconds, updating every second. The clock has a sleek, animated UI with circular rings representing the time.

## Features
- Displays real-time hours, minutes, and seconds
- AM/PM indicator and current date
- Animated circular rings for hours, minutes, and seconds
- Stylish and responsive UI with smooth transitions
- Works on all modern web browsers

## Technologies Used
- HTML
- CSS (with animations & gradients)
- JavaScript (Vanilla JS)

## Installation & Usage
1. Download or clone this repository:
   ```sh
   git clone <repository-url>
   ```
2. Open `digital_clock.html` in a web browser.
3. The clock will automatically update in real time.

## File Structure
```
📂 Real-Time Clock
│── digital_clock.html  # Main HTML file
│── style.css           # Styling with animations
│── script.js           # JavaScript logic for real-time updates
│── README.md           # Documentation (this file)
```

## How It Works
1. **Updating Time**
   - The `script.js` file fetches the current time using `Date()` and updates the display every second.
2. **Animating Clock Rings**
   - The CSS and JavaScript rotate circular rings to match the seconds, minutes, and hours.
3. **Date Display**
   - The current date is displayed in a user-friendly format.

## Live Demo
To host the clock on GitHub Pages:
1. Push this repository to GitHub.
2. Go to **Settings** > **Pages**.
3. Select the `main` branch and save.
4. Your live demo will be available at:
   ```
   https://your-username.github.io/repository-name/
   ```

## Future Enhancements
- Add customizable themes (light/dark mode)
- Option to switch between 12-hour and 24-hour format
- Sound effects for ticking seconds

## License
This project is open-source and free to use under the MIT License.

