# Bootstrap and HTML Calculator

A responsive and interactive arithmetic calculator developed as part of a Web Development Internship project.

## About the Project

The **Bootstrap and HTML Calculator** demonstrates the use of HTML5, CSS, Bootstrap 5, JavaScript, and jQuery to build a modern, grid-based calculator interface.

The application performs basic arithmetic operations while displaying the current input, expression, and evaluated result in the calculator display.

## Features

- Addition
- Subtraction
- Multiplication
- Division
- Decimal input
- Clear/CE and Delete controls
- Displays the current input, expression, and final result
- Supports both mouse/button input and keyboard events
- Responsive Bootstrap-based grid layout
- Dark calculator display with a clean button layout

## Technologies Used

- **HTML5** – Structure and semantic layout
- **CSS** – Custom calculator styling
- **Bootstrap 5.3.8** – Grid layout, spacing, alignment, and responsiveness
- **JavaScript** – Calculator logic and mathematical evaluation
- **jQuery 3.7.1** – DOM manipulation and event handling

## Project Structure

```text
html-calculator/
└── vendor/
    ├── bootstrap-5.3.8-dist/
    ├── jquery/
    └── index.html
```

> The repository structure above reflects the project files uploaded for this project.

## How It Works

The calculator maintains three main pieces of display information:

1. The number currently being entered
2. The saved mathematical expression
3. The final evaluated value

Button clicks and keyboard events are handled through jQuery event listeners. Operators build the expression, while the `=` operation evaluates the expression and displays the result.

## Methodology

The project was developed using a modular approach:

- **Wireframing:** A 4-column calculator button layout was planned.
- **Visual Design:** A dark display and light-colored buttons were used for contrast.
- **Event Handling:** Keyboard and screen-click inputs are connected to the same calculator logic.
- **Mathematical Evaluation:** Input expressions are evaluated to produce the final result.

## Screenshots

### Calculator Interface

![Calculator Interface](screenshots/calculator-screenshot-15.jpeg)

### Addition

![Addition](screenshots/calculator-screenshot-16.jpeg)

### Multiplication

![Multiplication](screenshots/calculator-screenshot-17.jpeg)

### Subtraction

![Subtraction](screenshots/calculator-screenshot-18.jpeg)

### Division

![Division](screenshots/calculator-screenshot-19.jpeg)

## Project Outcome

The project successfully demonstrates a functional and responsive calculator interface using Bootstrap and jQuery. It provided practical experience in UI state management, event handling, grid-based layouts, and interactive JavaScript logic.

## Author

**Sowmya C**

**Domain:** Web Development – Front-End

**Internship:** 1Stop EduTech – Internship Cohort 2026
