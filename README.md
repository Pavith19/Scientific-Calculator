

# Scientific Calculator

Welcome to the Scientific Calculator repository! This fully functional calculator, built with HTML, CSS and JavaScript, provides basic arithmetic operations, advanced math functions and supports both keyboard and mouse input.

<br>
<br>
<p align="center">
  <a href="https://github.com/Pavith19/Scientific-Calculator/">
    <img src="images/calculator.png" alt="Scientific Calculator" width="590" height="450">
  </a>
</p>

## Features

- **Basic Arithmetic Operations:** Addition, subtraction, multiplication, division, square roots and exponents.
- **Advanced Mathematical Functions:** sin, cos, tan, log, ln, etc.
- **Constants:** π, e.
- **Keyboard Input Support:** Seamless integration with keyboard inputs.
- **Smart Input Interpretation:** Understands inputs even without proper parentheses or multiplication signs.
- **Parentheses Balancing Check:** Ensures all parentheses are balanced using a Stack data structure.
- **Intelligent Backspace Functionality:** Context-sensitive backspace action.

## Key Highlights

### 🚀 Smart Backspace
The back button works intelligently. If pressed after a calculation, it clears the entire input. Otherwise, it deletes only the last character.

### 🚀 Intelligent Input Interpretation
The calculator can understand user inputs even without proper parentheses or multiplication signs. For example:

```sh
  15√(3+5!7π)sin(60°)^ln(log(5)e)7!  -->  15 × √(3 + 5! × 7 × π) × sin(60°) × ln(log(5) × e) × 7!

  4²3²√(5+6)  -->  4² × 3² × √(5 + 6)

  4^(3πe)  -->  4^(3 × π × e)

```

### 🚀 Parentheses Balancing
The calculator checks if all parentheses are balanced in the input expression using a Stack data structure. It displays appropriate errors for unbalanced parentheses:

 ```sh
    abs(-5)) ---> Error displayed: closing bracket has been used before an opening bracket.

    (abs(-5) ---> Error displayed: brackets are not balanced.
 ```

### 🚀 Keyboard Input
The calculator supports input through both mouse clicks and keyboard button presses.



