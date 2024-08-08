# Count Mate
## Overview
**Count Mate** is a simple web-based counter application that allows users to increment a counter and save the values for future reference. The app is built using HTML, CSS, and JavaScript, providing a minimalistic interface with basic functionality.

## Features
  - **Increment Counter**: Click the "INCREMENT" button to increase the counter by 1.
  - **Save Counter**: Click the "SAVE" button to save the current counter value and reset the counter to zero.
  - **View Previous Entries**: Saved values are displayed below the buttons as a series of entries.

## File Structure
The project consists of the following files:
  - index.html: Contains the structure of the webpage.
  - index.css: Contains the styles for the webpage.
  - index.js: Contains the JavaScript logic for the counter and save functionalities.
  - counting.png: Contains an image of coloured people.

## Code Explanation
**index.html**
This file defines the structure of the webpage. It includes:

  - A div container that holds the main content.
  - A heading (h1) for the title "Count Mate".
  - A h2 element with the ID count-el to display the current counter value, initialized at 0.
  - Two buttons:
    - INCREMENT button with an onclick event that calls the increment() function.
    - SAVE button with an onclick event that calls the save() function.
    - A paragraph (p) element with the ID save-el that shows the saved entries.

## Usage
**To use this application**:
  - Open the index.html file in a web browser.
  - Click the "INCREMENT" button to increase the counter.
  - Click the "SAVE" button to save the current count and reset the counter.
  - The saved entries will appear below the buttons, showing a history of all saved counts.

## Future Enhancements
  - Styling: Add CSS to enhance the visual appearance of the application.
  - Persistent Storage: Implement local storage to save the counter values even after refreshing the page.
  - Clear History: Add a button to clear the saved entries.

## License
- This project is free to use and modify for any purpose.

- Feel free to enhance and adapt it to your needs!
