# bmiCalculator
# JavaFX BMI Calculator

A JavaFX application for calculating Body Mass Index (BMI). This application provides a user-friendly and intuitive interface to calculate BMI and display the corresponding BMI category.

<img width="343" alt="Screenshot 2023-11-03 at 11 02 23" src="https://github.com/PorvaniVafo/bmiCalculator/assets/119600452/b008b8b4-a1d8-44e8-8c0d-3c7f16279725">

## Features

- Accurate BMI calculation using the formula: BMI = 703 * (weight in lbs / (height in inches)^2)
- BMI category classification (Underweight, Normal weight, Overweight, Obese)
- User-friendly and intuitive interface with error handling and data validation
- Ability to clear input fields and exit the application
- Information dialog about the BMI calculator

## Usage

1. Launch the application.
2. Enter your weight in pounds (lbs) and height in inches (in) into the respective input fields.
3. Click the "Calculate" button to compute your BMI.
4. The calculated BMI value and category will be displayed.
5. You can clear the input fields by clicking the "Clear" button.
6. To exit the application, click the "Exit" option in the menu.

## Proper BMI Calculation

The application calculates the BMI using the formula: BMI = 703 * (weight / (height^2)).

## Error Handling and Data Validation

- The application handles invalid input gracefully, displaying "Invalid input" when weight or height is not a valid number.
- It checks for weight and height values greater than zero to ensure valid input.

## BMI Categories

The application classifies BMI into the following categories:

- Underweight (BMI < 18.5)
- Normal weight (18.5 <= BMI < 24.9)
- Overweight (25 <= BMI < 29.9)
- Obese (BMI >= 30)

## Menu Options

- "Clear" menu option clears the input fields and the displayed BMI information.
- "Exit" menu option closes the application.

## Code Organization

The code follows proper Java OOP principles with separate methods for BMI calculation, error handling, and menu actions. The controller class organizes the application logic effectively.

## Documentation

The code is documented for clarity and readability. Each method and class is documented to describe its purpose and usage.

## Author

Mokhammad Parvani Vafa

## License


## Acknowledgments

- Thanks to [List of individuals or resources] for inspiration and support.

