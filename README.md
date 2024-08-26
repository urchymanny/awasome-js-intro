# JavaScript Basics Documentation

This documentation covers the basic concepts of JavaScript including data types, operations, and control structures. By the end of this document, you'll have a fundamental understanding of JavaScript and how to work with variables, data types, and operators.

## 1. Output Values to the Browser Console

In JavaScript, you can output values to the browser's console for debugging purposes using the `console.log()` function. This is very useful for inspecting values during code execution.

```javascript
console.log("Uchenna Mba's Website!");
```

You can also trigger a browser alert with the `alert()` function, though this is often used sparingly:

```javascript
// alert("Hello World");
```

## 2. JavaScript Data Types

JavaScript has several built-in data types, which can be divided into primitive types and objects.

### 2.1 Primitive Types

1. **String**: Represents text data. Strings are sequences of characters enclosed in quotes.
   ```javascript
   let greeting = "Hello There.... sinfonfongonghon \nsondsondonsdpn";
   ```

2. **Number**: Represents both integer and floating-point numbers.
   ```javascript
   let integer = 100000000000000000000000;
   let float = 3.14;
   ```

3. **BigInt**: Used for representing integers with arbitrary precision.
   ```javascript
   let bigIntNumber = 1234567890123456789012345678901234567890n;
   ```

4. **Boolean**: Represents logical values - `true` or `false`.
   ```javascript
   let isJavaScriptFun = true;
   ```

5. **Undefined**: A variable that has been declared but not assigned a value.
   ```javascript
   let notDefined;
   ```

6. **Null**: Represents the intentional absence of any object value.
   ```javascript
   let emptyValue = null;
   ```

7. **Symbol**: Represents a unique and immutable value, often used as object property keys.

### 2.2 Objects

Objects are collections of properties, and an array is a type of object in JavaScript.

1. **Array**: An ordered collection of values (elements). Each element has an index, starting from 0.
   ```javascript
   let people = ["Uchenna", "Awa", "John", true, 54, null];
   ```

2. **Object**: A collection of key-value pairs, where each key is a string (or symbol) and the value can be of any type.
   ```javascript
   let person = {
       name: "Uchenna",
       age: 54,
       place_of_birth: null
   };
   ```

You can also create an array of objects:
```javascript
let peopleArray = [
    { name: "Uchenna", age: 54, place_of_birth: null }, 
    { name: "Victor", age: 54, place_of_birth: null }
];
```

## 3. Variables

In JavaScript, variables can be declared using `let`, `const`, or `var` (though `var` is generally avoided in modern code).

1. **let**: Declares a block-scoped, mutable variable.
   ```javascript
   let myNumber = 25;
   ```

2. **const**: Declares a block-scoped, immutable variable. Once a value is assigned, it cannot be changed.
   ```javascript
   const anotherNumber = 50;
   ```

## 4. Operators

Operators in JavaScript are used to perform operations on variables and values.

### 4.1 Arithmetic Operators

- `+`: Addition
- `-`: Subtraction
- `*`: Multiplication
- `/`: Division
- `%`: Modulo (remainder)

Example:
```javascript
let sum = 5 + 3;       // 8
let difference = 5 - 3; // 2
let product = 5 * 3;   // 15
let quotient = 5 / 3;  // 1.6667
let remainder = 5 % 3; // 2
```

### 4.2 Assignment Operators

- `=`: Assigns a value to a variable
- `+=`: Adds and assigns the result
- `-=`: Subtracts and assigns the result
- `*=`: Multiplies and assigns the result
- `/=`: Divides and assigns the result

Example:
```javascript
let number = 10;
number += 5;  // number is now 15
number -= 3;  // number is now 12
number *= 2;  // number is now 24
number /= 4;  // number is now 6
```

### 4.3 Comparison Operators

- `==`: Equal to
- `!=`: Not equal to
- `===`: Strict equal (checks both value and type)
- `!==`: Strict not equal (checks both value and type)
- `>`: Greater than
- `>=`: Greater than or equal to
- `<`: Less than
- `<=`: Less than or equal to

Example:
```javascript
5 == '5';   // true (type coercion)
5 === '5';  // false (no type coercion)
5 != '5';   // false (type coercion)
5 !== '5';  // true (no type coercion)
```

### 4.4 Ternary Operator

The ternary operator is a shorthand for an `if-else` statement. It takes three operands:
```javascript
condition ? expressionIfTrue : expressionIfFalse;
```

Example:
```javascript
let age = 18;
let canVote = (age >= 18) ? "Yes" : "No";
```

In this example, `canVote` will be `"Yes"` because `age` is 18.