# 🧮 Calculator

A clean, minimal calculator web app built with vanilla HTML, CSS, and JavaScript.

![Calculator Preview](preview.png)

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, division
- Percentage calculation (`%`)
- Delete last character (`DEL`)
- Clear all input (`AC`)
- Decimal point support
- Responsive, glassmorphism-inspired dark UI

## Tech Stack

- **HTML5** — Structure and layout
- **CSS3** — Styling with a dark gradient background and neumorphic buttons
- **JavaScript (Vanilla)** — Button logic and expression evaluation

## Project Structure

```
calculator/
├── index.html   # Main HTML file
├── style.css    # Styles and layout
└── script.js    # Calculator logic
```

## Getting Started

No build tools or dependencies required. Just open the project in a browser:

1. Clone or download the repository
2. Open `index.html` in any modern web browser

```bash
git clone https://github.com/your-username/calculator.git
cd calculator
open index.html   # macOS
# or
start index.html  # Windows
```

## How It Works

Button clicks are captured via event listeners. The input string is built up character by character and evaluated using JavaScript's `eval()` on pressing `=`. Special buttons (`AC`, `DEL`, `%`) are handled separately.

## Author

**Ashutosh Gupta**

## License

This project is open source and available under the [MIT License](LICENSE).
