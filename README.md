# lab-2-mobile-Applications-calculator

# Flutter Calculator App

## Overview
This is a simple calculator application built with Flutter. The app provides basic arithmetic operations including addition, subtraction, multiplication, and division. It features a user-friendly interface with a numeric keypad and function keys, resembling a traditional calculator. The app maintains the last computed value using persistent storage.

## How It Works
- The calculator allows users to input numbers using a 3x3 grid (1-9) and additional buttons for 0, clear entry (CE), and clear (C).
- Users can perform basic arithmetic operations (+, -, *, /).
- The result is displayed on an 8-digit screen.
- If an error occurs (e.g., division by zero), an error message is shown.
- The last computed value is saved and displayed when the app restarts using `SharedPreferences`.

## Key Files
- **`main.dart`**: The main entry point of the application containing the calculator logic and UI.
- **`pubspec.yaml`**: Defines the dependencies and package configurations.
- **`android/ios/web`**: Platform-specific configurations for different devices.

## Source and Modifications
- The base structure was created from a standard Flutter project.
- `main.dart` was modified to implement the calculator logic and UI.
- The **state persistence** feature was added using the `SharedPreferences` package to remember the last calculated value.
- **UI Enhancements** were made to ensure a structured, readable layout.
- **Error handling** was included to display messages like "ERROR" and "OVERFLOW" in the display.

## Why These Changes Were Made
- **State Persistence**: To improve user experience by keeping the last computed value available.
- **Enhanced UI**: To match the behavior of a physical calculator, making it intuitive to use.
- **Error Handling**: To provide clear feedback in cases of invalid operations like division by zero.

## Code Comments
- The code contains comments explaining:
  - The purpose of each function.
  - How button presses are handled.
  - How state persistence works.

This project showcases Flutter’s ability to create simple yet powerful applications with persistent state and a clean UI.

