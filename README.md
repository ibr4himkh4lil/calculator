# iOS Calculator

A simple calculator web app that mimics the look and feel of the iOS calculator, built with a single HTML file — no frameworks, no dependencies.

## Features

- iOS-style design: dark theme, rounded circular buttons, orange operator keys
- Basic operations: addition (+), subtraction (−), multiplication (×), division (÷)
- Percentage (%) and sign toggle (+/−)
- Decimal support
- Chained calculations
- Highlighted active operator
- Large display with exponential notation for big numbers
- Works on desktop and mobile (touch friendly)

## Usage

Open `index.html` in any modern browser, or visit the live demo:

**https://ibr4himkh4lil.github.io/calculator/**

## How it works

The app is a single self-contained file (`index.html`) with embedded CSS and JavaScript. It uses simple state variables (`current`, `previous`, `operator`) to handle input and evaluation — no `eval()` needed.

## File structure

```
calculator/
├── index.html   # The entire app
└── README.md    # This file
```

## License

MIT
