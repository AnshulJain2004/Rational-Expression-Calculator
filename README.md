## Rational Expression Calculator

This repository contains a simple **Java console application** that performs arithmetic operations on two rational numbers (fractions). The project demonstrates the use of a custom `RationalNumber` class to handle tasks such as:

- **Creation** and **simplification** of rational numbers  
- **Arithmetic operations**: addition, subtraction, multiplication, division  
- **Absolute value** computation (`abs`)  
- **Conversion** to a floating-point representation (`toDouble`)  
- **Comparison** of two rational numbers  

### Features

1. **RationalNumber Class**  
   - Stores a fraction as two integers (`numerator` and `denominator`).  
   - Simplifies fractions automatically upon creation or after any arithmetic operation.  
   - Throws an `IllegalArgumentException` when the denominator is zero.  
   - Provides methods for arithmetic operations, absolute value, comparison, and conversion to `double`.

2. **Main Application**  
   - Prompts the user for two rational numbers in the `a/b` format.  
   - Validates input and gracefully handles errors (e.g., zero denominator, invalid format).  
   - Displays the results of arithmetic operations and some additional details (like absolute value and floating-point conversion).  

### How to Run

1. **Clone** or download this repository.  
2. **Compile** the Java files:
   ```bash
   javac Main.java RationalNumber.java
   ```
3. **Run** the application:
   ```bash
   java Main
   ```
4. **Follow** the on-screen prompts to enter two rational numbers (in `a/b` format).  

### Example

```
Enter the first rational number (in the format 'a/b'): 1/2
Enter the second rational number (in the format 'a/b'): -2/3
First rational number: 1/2
Second rational number: -2/3
Sum: -1/6
Difference: 7/6
Product: -1/3
Quotient: -3/4
Absolute value of first number: 1/2
Absolute value of second number: 2/3
First number as floating point: 0.5
Second number as floating point: -0.6666666666666666
```

### License

This project is available under the [MIT License](https://opensource.org/licenses/MIT). See the [LICENSE](LICENSE) file for details.

---
