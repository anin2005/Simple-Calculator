# Simple Python Calculator

## Overview

This is a basic Python calculator that performs four fundamental arithmetic operations:
- Addition
- Subtraction
- Multiplication
- Division

The calculator takes user input from the command line, performs the selected operation, and displays the result.

## Features

- **Addition**: Adds two numbers.
- **Subtraction**: Subtracts the second number from the first.
- **Multiplication**: Multiplies two numbers.
- **Division**: Divides the first number by the second (handles division by zero).

## Usage

1. **Clone the Repository** (if applicable):

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Run the Calculator Script**:

   Ensure you have Python installed (Python 3.x is recommended). Run the script using:

   ```bash
   python calculator.py
   ```

3. **Follow the Prompts**:

   - Choose an operation by entering the corresponding number (1, 2, 3, or 4).
   - Enter two numbers when prompted.
   - View the result displayed in the terminal.

## Code Explanation

- **Functions**: The script defines four functions (`add`, `subtract`, `multiply`, `divide`) for performing basic arithmetic operations.
- **User Input**: The `calculator()` function prompts the user to select an operation and input two numbers.
- **Operation Execution**: Based on user input, the corresponding arithmetic operation is performed, and the result is displayed.
- **Error Handling**: The `divide` function handles division by zero to prevent runtime errors.

## Example

Here’s an example of running the calculator:

```
Select operation:
1. Add
2. Subtract
3. Multiply
4. Divide
Enter choice (1/2/3/4): 1
Enter first number: 10
Enter second number: 5
10.0 + 5.0 = 15.0
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to submit issues and pull requests. Contributions are welcome!

## Contact

For any questions or feedback, please contact dasaninda62@gmail.com.
