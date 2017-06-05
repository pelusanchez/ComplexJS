# ComplexJS
Complex numbers in JavaScript.

## Set up

Include the *complex.js* file in your JavaScript project. Then you will be able to use the Complex Numbers.

## Use

Create a new Complex number:
```javascript
  var number1 = new Complex("2+3i");
  var number2 = new Complex("9-1i");
  var number3 = new Complex("1.3832-9.87i");
  
  // Add number1 to number2
  var result = number1.add(number2);
  
  // Subtract number1 from number2
  var result = number1.subs(number2);
  
  // Product
  var result = number1.mul(number2);
  
  // Module
  var module = number3.abs();
  
  // Angle
  var angle = number3.angle();
```

## To Do

### Basic operations
[x] Addition
[x] Subtraction
[x] Multiplication
[ ] Division
[x] Module
[x] Angle

### Functions
[x] Pow
[x] Exponent
[x] Sin
[x] Cos
[ ] Tan
