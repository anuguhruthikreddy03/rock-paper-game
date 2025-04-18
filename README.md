# ✊✋✌️ Rock Paper Scissors Game

A fun and interactive Rock-Paper-Scissors game built using **HTML**, **CSS**, and **Vanilla JavaScript**. The game lets you compete against the computer and keeps track of the scores with dynamic feedback and vibrant styling.

---



The `style.css` file defines the look and feel of the game interface. It is crafted to provide a clean, engaging, and responsive user experience. Here's a breakdown of its key features:

### ✏️ Key Styling Highlights

- **Layout and Structure**:
  - The body uses `flexbox` to center content vertically and horizontally.
  - Elements are stacked in a column for a clean, readable interface.

- **Typography**:
  - Uses `Arial, Helvetica, sans-serif` for clean and readable fonts.
  - Bold text enhances visual clarity.

- **Buttons (`.choices button`)**:
  - Extra-large emojis (📄 ✊ ✂️) represent each move.
  - Circular buttons styled with `border-radius: 250px`.
  - Interactive hover effects with smooth transitions.

- **Displays (`#playerDisplay`, `#computerDisplay`, `#resultDisplay`)**:
  - Large font sizes for easy readability.
  - Result display is prominently styled with a 5rem font size.

- **Score Indicators (`.scoreDisplay`)**:
  - Separate colors for player and computer scores:
    - 🟢 Green for the player (`#playerScoreDisplay`)
    - 🔴 Red for the computer (`#computerScoreDisplay`)

- **Win/Loss Feedback**:
  - Winning adds the `greenText` class to the result.
  - Losing adds the `redText` class, enhancing user feedback.

---

## 🧠 How It Works

- Player clicks one of the buttons: Rock, Paper, or Scissors.
- The computer randomly selects a move.
- The result is calculated and displayed.
- Scores are updated based on the outcome.

---

