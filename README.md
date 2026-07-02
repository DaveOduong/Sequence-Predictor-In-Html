# Sequence Pattern Predictor

A lightweight web application that analyzes a sequence of numbers, detects common mathematical patterns, and predicts the next three values.

Built using **HTML, CSS, and JavaScript**, the application recognizes multiple sequence types and displays the detected pattern along with a confidence score.

---

## Features

- Detects common number sequence patterns
- Predicts the next three numbers
- Displays confidence level for each prediction
- Clean and responsive user interface
- No external libraries required
- Runs entirely in the browser

---

## Supported Patterns

The application currently recognizes:

- Constant Sequence
- Arithmetic Sequence
- Geometric Sequence
- Fibonacci Sequence
- Perfect Squares
- Perfect Cubes
- Triangular Numbers
- Prime Numbers
- Quadratic Sequences
- Alternating Arithmetic Sequences

---

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript

---

## How It Works

1. Enter a sequence of numbers separated by spaces or commas.
2. Click **Analyze & Predict**.
3. The program compares the sequence against a collection of mathematical pattern algorithms.
4. If a matching pattern is found, it displays:
   - Detected pattern
   - Confidence level
   - Next three predicted numbers

If no known pattern is detected, the application suggests entering a longer sequence.

---

## Example

### Input

```
2, 4, 6, 8
```

### Output

```
Detected Pattern:
Arithmetic Sequence

Confidence:
100%

Next Numbers:
10, 12, 14
```

---

## Project Structure

```
Sequence-Pattern-Predictor/
│
├── index.html
└── README.md
```

---

## Pattern Detection Strategy

Each sequence type is implemented as an independent pattern module containing:

- Pattern name
- Confidence score
- Matching algorithm
- Prediction algorithm

This modular approach makes it easy to add additional sequence types without modifying the core prediction logic.

---

## Future Improvements

- Polynomial sequence detection
- Recursive sequence analysis
- AI-assisted pattern recognition
- User-defined custom formulas
- Sequence explanation step-by-step
- Graph visualization
- Export prediction results
- Dark mode
- Prediction history

---

## Requirements

- Any modern web browser
- No installation required
- No internet connection required

---

## Running the Project

1. Download or clone the repository.
2. Open `index.html` in your preferred web browser.
3. Enter a sequence.
4. Click **Analyze & Predict**.

---

## Educational Applications

This project can be used for:

- Mathematics learning
- Algorithm demonstrations
- Pattern recognition exercises
- Programming education
- Number sequence analysis

---

## License

This project is open source and may be modified and distributed for educational and personal use.
