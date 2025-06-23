# faulty-calc

# Faulty Calculator

A simple Node.js command-line calculator that sometimes gives the wrong answer on purpose!  
This calculator performs basic arithmetic operations (`+`, `-`, `*`, `/`), but with a twist:  
**50% of the time, it will intentionally perform the wrong operation.**

## How It Works

- When you enter two numbers and an operator, the calculator will:
  - 50% chance: perform the correct operation.
  - 50% chance: perform a "faulty" operation:
    - `+` (add) → subtracts instead
    - `-` (subtract) → divides instead
    - `*` (multiply) → adds instead
    - `/` (divide) → raises to the power instead

## Example

```
Enter first number: 10
Enter operator (+, -, *, /): *
Enter second number: 5
Result: 15
```
*(Instead of 50, it added due to the faulty logic!)*

## Usage

1. **Clone the repository:**
    ```
    git clone https://github.com/yourusername/faultycalc.git
    cd faultycalc
    ```

2. **Run the calculator:**
    ```
    node faultycalc.js
    ```

3. **Follow the prompts to enter numbers and an operator.**

## Requirements

- [Node.js](https://nodejs.org/) (v12 or higher)

## License

MIT

---
*This project is for fun and
