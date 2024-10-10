# BMI Calculator

A simple and interactive **BMI Calculator** to calculate the Body Mass Index (BMI) based on user inputs of height and weight. The calculator provides the BMI value and categorizes it based on standard BMI classifications such as underweight, normal, overweight, and obesity.

## Features

- **BMI Calculation**: The app calculates BMI based on height (in meters) and weight (in kilograms).
- **BMI Categories**: The result is classified into various health categories (Underweight, Normal, Overweight, Obesity, Severe Obesity).
- **Interactive UI**: Provides a simple form with two buttons: "Calculate" to compute the BMI and "Clear" to reset the inputs.
- **Responsive Design**: Adapts well to various screen sizes.

## Technologies Used

- **HTML5**: Markup language for structuring the page.
- **CSS3**: Used to style the page and create a responsive layout.
- **JavaScript**: Handles the BMI calculation and DOM manipulation for dynamic updates.

## How It Works

1. **Input**: 
    - The user inputs their height in meters (e.g., "1.75") and weight in kilograms (e.g., "70.5").
2. **Calculation**:
    - After pressing the "Calculate" button, the BMI is calculated using the formula:  
      BMI = Weight (kg) / [Height (m)]²

3. **Result**: 
    - The calculated BMI value is displayed along with a category (e.g., Underweight, Normal, Overweight).
    - A table shows the classification range for different BMI values.
4. **Reset**: 
    - The user can press the "Clear" button to reset the form or "Back" to go back to the input form after viewing the result.

## BMI Classifications

The following are the BMI ranges used in the application:

| BMI Range       | Classification    | Obesity Level |
|-----------------|-------------------|---------------|
| Less than 18.5  | Underweight        | 0             |
| 18.5 - 24.9     | Normal             | 0             |
| 25.0 - 29.9     | Overweight         | I             |
| 30.0 - 39.9     | Obesity            | II            |
| Greater than 40 | Severe Obesity     | III           |

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
