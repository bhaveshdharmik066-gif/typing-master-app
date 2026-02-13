# Typing Master

A professional typing speed test website built with React and Vite.

## Features

- **Live Typing Test**: Real-time feedback on typing speed and accuracy.
- **Dynamic Mistake Highlighting**: Visual cues for correct, incorrect, and active characters.
- **Stats Tracking**: Live WPM (Words Per Minute), Accuracy, and Time Left.
- **Difficulty Levels**: Choose between Easy, Medium, and Hard tests.
- **Theme Support**: Toggle between Dark and Light modes.
- **Responsive Design**: Works on desktop and mobile.

## Project Structure

- `src/components/`: Reusable UI components (Attributes, Header, TypingArea, etc.)
- `src/hooks/`: Custom hooks for game state management (`useTypingGame`).
- `src/App.jsx`: Main application layout.
- `src/index.css`: Global styles and theme variables.

## How to Run

1.  **Install Dependencies** (if you haven't already):
    ```bash
    npm install
    ```

2.  **Start Development Server**:
    ```bash
    npm run dev
    ```

3.  **Open in Browser**:
    Visit `http://localhost:5173/` (or the URL shown in standard output).

## Technologies Used

- React 18
- Vite
- CSS Modules / Variables
- Google Fonts (Outfit)
