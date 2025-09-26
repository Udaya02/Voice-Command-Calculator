# Voice-Activated Calculator

This is a web-based calculator application that can perform a wide range of mathematical calculations based on voice or text commands. It uses Flask for the web framework and the SpeechRecognition library to process voice input.

Features
Basic Arithmetic: Addition, subtraction, multiplication, and division.

Complex Expressions: Evaluates complex mathematical expressions like (5 + 3) \* 2.

Power Functions: Calculate squares, cubes, square roots, cube roots, and custom powers.

Trigonometry: Supports sine, cosine, tangent, and their hyperbolic counterparts (sinh, cosh, tanh).

Logarithms: Calculates the logarithm of a number to a given base.

Factorials: Computes the factorial of a number.

Web Interface: A simple and clean user interface to input commands via text or voice.

Voice Commands: Simply speak your calculation, and the app will process it.

## Project Structure

The project is organized into several modules, each responsible for a specific set of calculations:

app.py: The main Flask application file. It handles web routes, processes user commands by interpreting the text, and calls the appropriate calculation functions.

basic_calculation.py: Contains functions for basic arithmetic operations (+, -, \*, /).

functions_for_power_calculation.py: Includes functions for calculating powers, squares, cubes, and roots.

factorial.py: A dedicated module for calculating factorials.

trigonometry.py: Houses all the trigonometric and logarithmic functions.

### Prerequisites:

Python 3.x

pip (Python package installer)

Required Python packages:

pip install Flask SpeechRecognition pyttsx3

How to Run
Navigate to the project directory in your terminal.

Run the main application file:

python app.py

You can now type in your commands or click the "Speak" button to use voice commands.
