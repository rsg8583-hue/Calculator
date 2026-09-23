# Calculator

A simple, intuitive GUI-based calculator application built with Python and Kivy framework. This calculator provides a clean interface for performing basic arithmetic operations with an interactive button layout.

## Features

- **Interactive GUI Interface**: User-friendly graphical interface with clickable buttons
- **Basic Arithmetic Operations**: Supports addition (+), subtraction (-), multiplication (*), and division (/)
- **Decimal Support**: Allows calculations with decimal numbers
- **Real-time Display**: Shows input and calculation results instantly
- **Clear Function**: Reset button to clear the current calculation
- **Error Handling**: Gracefully handles syntax errors in expressions
- **Cross-platform**: Works on Windows, macOS, and Linux

## Requirements

- Python 3.6 or higher
- Kivy 2.0.0 or higher

### System Dependencies

Kivy may require additional system dependencies depending on your operating system. Please refer to the [official Kivy installation guide](https://kivy.org/doc/stable/gettingstarted/installation.html) for detailed requirements.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/phantomop26/Calculator.git
   cd Calculator
   ```

2. **Install Python dependencies**:
   ```bash
   pip install kivy
   ```

   Or install a specific version:
   ```bash
   pip install kivy==2.1.0
   ```

3. **Verify installation**:
   ```bash
   python -c "import kivy; print(kivy.__version__)"
   ```

## Usage

To run the calculator application:

```bash
python Calculator.py
```

### Using the Calculator

1. **Launch** the application using the command above
2. **Click number buttons** (0-9) to input numbers
3. **Click operation buttons** (+, -, *, /) to select operations
4. **Click the decimal button** (.) for decimal numbers
5. **Click equals** (=) to evaluate the expression
6. **Click Clear** to reset the calculator

### Example Calculations

- Simple addition: `5 + 3 =` → Result: `8`
- Decimal operations: `12.5 * 2 =` → Result: `25.0`
- Multiple operations: `10 + 5 * 2 =` → Result: `20`

## Project Structure

```
Calculator/
├── Calculator.py       # Main application file containing the Kivy app logic
└── README.md          # Project documentation
```

### Code Overview

- **myApp**: Main application class inheriting from Kivy's App class
- **build()**: Creates the calculator UI with:
  - Output label for displaying calculations and results
  - Grid layout of number and operation buttons
  - Clear button for resetting the display
  - Event handlers for button presses and calculation evaluation

## Tests

Currently, this project does not include automated tests. To manually test the calculator:

1. Launch the application
2. Test basic operations (addition, subtraction, multiplication, division)
3. Test decimal number calculations
4. Test the clear function
5. Test error handling by entering invalid expressions

### Testing Checklist

- [ ] Addition works correctly
- [ ] Subtraction works correctly
- [ ] Multiplication works correctly
- [ ] Division works correctly
- [ ] Decimal numbers are supported
- [ ] Clear button resets the display
- [ ] Syntax errors are handled gracefully

## Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes** and commit them:
   ```bash
   git commit -m "Add your descriptive commit message"
   ```
4. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```
5. **Open a Pull Request** with a clear description of your changes

### Contribution Ideas

- Add scientific calculator functions (sin, cos, tan, sqrt, etc.)
- Implement keyboard input support
- Add calculation history feature
- Improve error messages
- Add unit tests
- Enhance UI/UX design
- Add themes or customization options

## License

This project is open source and available for educational and personal use. Please check with the repository owner for specific licensing terms.

## Contact

- **Repository**: [https://github.com/phantomop26/Calculator](https://github.com/phantomop26/Calculator)
- **Issues**: [https://github.com/phantomop26/Calculator/issues](https://github.com/phantomop26/Calculator/issues)

For questions, suggestions, or bug reports, please open an issue on GitHub.