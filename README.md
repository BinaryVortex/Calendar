# Calendar

A clean, responsive calendar built using HTML, CSS, and JavaScript.

![Calendar Screenshot](Screenshot%202024-06-14%20233346.png)

## Overview

This is a lightweight, client-side calendar that displays the current month and allows navigation between months. It uses plain JavaScript for date calculations and DOM updates, with CSS for styling.

## Features

- Shows month and year in the header
- Displays days of the week and dates for the selected month
- Includes previous/next controls to navigate months
- Highlights the current day
- Simple, responsive layout — no frameworks required

## Technologies

- JavaScript
- HTML
- CSS

## Usage

To run the calendar locally:

1. Clone or download the repository.
2. Open `index.html` in your browser.

No build steps or dependencies are required.

## How it works (brief)

- script.js calculates the first and last day of the current month and renders the appropriate day elements.
- Inactive days from the previous and next month are shown with a muted style.
- Clicking the previous/next icons updates the current month and re-renders the calendar.

Files of interest:
- `index.html` — markup
- `style.css` — styles
- `script.js` — calendar logic

## Customization

- Change colors and typography in `style.css`.
- Modify `script.js` to add events, click handlers, or other features (e.g., recurring events or localStorage persistence).

## Contributing

Contributions are welcome. If you want to add features or improvements, open a pull request or create an issue describing the change.

## License

No license specified. Add a LICENSE file to this repository if you want to apply an open-source license.

---

Made with ❤️ by BinaryVortex
