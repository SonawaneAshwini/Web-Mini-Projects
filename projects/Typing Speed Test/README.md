# Typing Speed Test

A web-based application designed to help users improve their typing speed and accuracy through various levels of difficulty. The application tracks progress, provides real-time feedback, and offers a dashboard to view achievements.

## Features

- **Interactive Typing Test:** Users can practice typing with dynamically generated sentences.
- **Progress Tracking:** The application tracks the user's progress, including words per minute (WPM) and accuracy.
- **Multiple Levels:** The test includes multiple levels with increasing difficulty.
- **Achievements:** Users can view their achievements on the dashboard.
- **Responsive Design:** Optimized for both desktop and mobile devices.

## Demo

[Link to demo](https://dzc2s7.csb.app/dashboard.html)

![image](https://github.com/user-attachments/assets/1a8a77f2-8226-4841-a1b2-759c1ad10eb4)

![image](https://github.com/user-attachments/assets/61dd7115-e73d-453d-ab21-b1ed77b5a852)

![image](https://github.com/user-attachments/assets/019d6cab-20d9-4d83-8d73-efab38ff47e9)

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/typing-speed-test.git
    ```

2. **Navigate into the project directory:**
    ```bash
    cd typing-speed-test
    ```

3. **Open  in a web browser to start the game:**
    ```bash
    open index.html
    ```

## Usage

1. Open the  file in your browser.
2. Start typing in the provided text area to begin the test.
3. The application will track your WPM and accuracy in real-time.
4. Complete the level to see your results and move to the next level.
5. View your achievements on the dashboard by navigating to .

## Customization

- **Styling:** Modify the appearance of the application by editing `css/style.css`.
- **Functionality:** Extend or change the behavior of the app by editing  and .
- **Sentences:** Update the sentences used in the test by editing .

## File Structure

```bash
typing-speed-test/
│
├── app.js              # Core JavaScript logic for the application
├── css/
│   ├── style.css       # CSS file for styling the application
├── dashboard.html      # HTML file for the achievements dashboard
├── data/
│   ├── sentences.json  # JSON file containing sentences for the typing test
├── index.html          # Main HTML file for the typing test
├── js/
│   ├── dashboard.js    # JavaScript file for the dashboard functionality
│   ├── main.js         # JavaScript file for the main typing test functionality
└── README.md           # Project documentation
