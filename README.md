# Calculator

A small four-function calculator, originally written in Python with the [Kivy](https://kivy.org) UI framework, plus a browser version of the same layout that runs without installing anything.

## Features

- Addition, subtraction, multiplication and division
- Decimal numbers
- A Clear button to reset the display
- Browser version supports keyboard input: digits and operators, `Enter` to evaluate, `Backspace` to delete, `Esc` to clear

## Run the Python version

Requires Python 3 and Kivy.

```bash
pip install kivy
python Calculator.py
```

## Run the browser version

Open `index.html` in any browser. It's a single file with no dependencies.

## Project structure

| File | Description |
| --- | --- |
| `Calculator.py` | Desktop calculator built with Kivy |
| `index.html` | Project webpage with a browser version of the calculator |

## How it works

The Kivy app lays out a 4×4 grid of buttons below an output label. Pressing a button appends its symbol to the label, and `=` evaluates the expression with Python's `eval`.

The browser version keeps the same button order but evaluates expressions with a small parser that only accepts numbers and `+ - * /`, so it never runs arbitrary code.
