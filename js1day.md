# JS in 1 day

learn the basics for frameworks
search things you wanna know more about

## Environment setup

- ### IDE => [vscode](https://code.visualstudio.com)

  - #### extensions

    - [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

    - [JavaScript and TypeScript Nightly](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-next)

    - [Halcyon Theme](https://marketplace.visualstudio.com/items?itemName=brittanychiang.halcyon-vscode)

    - [Nebula Theme](https://marketplace.visualstudio.com/items?itemName=ChirtleLovesDolls.nebula-theme)

    - [Icon](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

  - #### settings
    - `Auto Save => onFocusChange`
    - `Format On Save => true`
    - `Default Formatter => Prettier`

- ### Shell

  - ### `Window` install [git bash](https://git-scm.com/downloads)
  - ### `Mac` use _bash/zsh_
    use git for sharing code between computers

- ### Node => [node.js](https://nodejs.org/en/download/)
  - use node.js for server side code
  - use npm for package management

# Get Started

1. create a file called `index.js`
2. open it with `vscode`
3. type this line of code in your file
   ```js
   console.log("hello world");
   ```
4. open a terminal and run

   ```
   node index.js
   ```

   ### Save your result here

   example:

   ```
   // paste your output here

   hello world
   ```

# Basics

## Variables

[ref](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Grammar_and_types#Variables)

- `var` => global variables
- `let` => block scope
- `const` => block scope, immutable

  examples:

  ```js
  var a = 1;
  let boatCount = 2;
  const chosenOne = 3;

  console.log("ahaha", a, b, c);
  ```

> let default = useCamelCaseAsDefaultVariableNames

---

## Data types

# `string` => `"hello world"`

[ref](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)

- ## What
  _string is a sequence of characters, (text, paragraph)_
- ## Usage

  ```js
  let name = "John";
  console.log(name);
  ```

  output

  ```
  // paste your output here


  ```

- ## Methods

  examples:

  - `.length` => number of characters in the string
  - `.toUpperCase()` => `HELLO WORLD`
  - `.toLowerCase()` => `hello world`
  - `.charAt(index)` => `h`
  - `.indexOf(char)` => `0`
  - `.lastIndexOf(char)` => `11`
  - `.substring(start, end)` => `hello`
  - `.slice(start, end)` => `hello`

- ## Examples

  ```js
  const name = "John";
  console.log(name.length);
  console.log(name.toUpperCase());
  console.log(name.charAt(2));
  ```

  output (try with more methods)

  ```
  // paste your output here


  ```

# `number` => `1`

[ref](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)

- ## What
  _number is a sequence of digits_
- ## Usage

  ```js
  let age = 25;
  console.log(age);

  console.log(age * 2);
  ```

  output

  ```
  // paste your output here


  ```

# Math

- ## Methods

  - `.toFixed(digits)` => `25.00`
  - `.toExponential(digits)` => `2.5e+1`
  - `.toPrecision(digits)` => `25`
  - `.toString()` => `25`
  - `.valueOf()` => `25`

- ## Examples

  ```js
  const age = 25;
  console.log(age.toFixed(2));
  console.log(age.toExponential(2));
  ```

  output
  (try with more methods)

  ```
  // paste your output here


  ```

# `boolean` => `true`

[ref](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)

- ## What
  _boolean is either true or false_
- ## Usage

  ```js
  let isValid = true;
  console.log(isValid);
  ```

  output

  ```
  // paste your output here


  ```

# `null` => `null`

[ref](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/null)

- ## What
  _null is a value that represents nothing_
- ## Usage

  ```js
  let name = null;
  console.log(name);
  ```

  output

  ```
  // paste your output here


  ```

# `undefined` => `undefined`

- ## What
  _undefined is a value that represents nothing_
- ## Usage

  ```js
  let name;
  console.log(name);
  ```

  output

  ```
  // paste your output here


  ```

# `object` => `{}`

[reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)

- ## What

  _object is a collection of key-value pairs_
  it can be used to store data

- ## Usage

  declaring an object

  ```js
  let person = {
    name: "Dol",
    age: 14,
    isValid: true,
  };
  console.log(person);
  ```

  output

  ```
  // paste your output here


  ```

  accessing an object

  ```js
  let person = {
    name: "John",
    age: 25,
    isValid: true,
  };
  console.log(person.name);
  ```

  output

  ```
  // paste your output here


  ```

  ## Methods

  [`Object.keys()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys)

  [`Objects.values()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/values)

> try using `Object.keys()` and `Object.values()`

# `array` => `[]`

- ## What

  _array is a collection of values_

- ## Usage

  ```js
  let names = ["John", "Jane", "Mary"];
  console.log(names);
  ```

  output

  ```
  // paste your output here


  ```

- ## Methods

  [`Array.push()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push)

  [`Array.pop()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop)

  [`Array.shift()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/shift)

  [`Array.unshift()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/unshift)

  [`Array.splice()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice)

  [`Array.slice()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice)

  [`Array.reverse()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reverse)

  [`Array.sort()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)

  - ### Exercises

    try using some of the methods above

  - ### Examples

    ```js
    const names = ["John", "Jane", "Mary"];
    names.push("Bob");
    console.log(names);
    ```

    output

    ```
    // paste your output here



    ```

  - ## Looping array

    - #### `forEach()`

      [`Array.forEach()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)

      ```js
      const names = ["John", "Jane", "Mary"];
      names.forEach(function (name) {
        console.log(name);
      });
      ```

      output

      ```
      // paste your output here



      ```

    - #### `map()`

      [`Array.map()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)

      ```js
      const names = ["John", "Jane", "Mary"];
      const namesUpperCase = names.map(function (name) {
        return name.toUpperCase();
      });
      console.log(namesUpperCase);
      ```

      output

      ```
      // paste your output here


      ```

    - #### `filter()`

      [`Array.filter()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)

      ```js
      const names = ["John", "Jane", "Mary"];
      const namesUpperCase = names.filter(function (name) {
        return name.charAt(0) === "J";
      });
      console.log(namesUpperCase);
      ```

# `function` => `function() {}`

- ## What

  _function is a reusable block of code_

  > Functions take input run a block of code and return a value (or nothing)

- ## Usage

  ```js
  function sayHello() {
    console.log("hello");
    console.log("bonjour");
  }
  sayHello();
  ```

  a function named `sayHello` is created\
  it takes no input/parameters\
  ran the block of code\
  it returns nothing

  The function is called by using the name of the function followed by parentheses\
  EX: `sayHello()`

- ## Examples

  ```js
  function sayHello() {
    return "hello";
  }

  console.log(sayHello());

  function sayHelloTo(name) {
    let text = "hello " + name;
    console.log(text);
    return text;
  }
  sayHello("John");

  function sayHelloNameAge(name, age) {
    console.log("hello " + name + " you are " + age + " years old");
  }
  sayHelloNameAge("John", 25);
  ```

- ### Exercise

  - explain how the functions above work (what does it call, what it takes as input, what does it return)

    answer

  ```
  // paste your output here


  ```

- ## Functions with parameters

  ```js
  function sayHello(name) {
    console.log("hello " + name);
  }
  sayHello("John");
  ```

  output

  ```
  // paste your output here


  ```

- ## Arrow Functions

  write less, do more

  `() => {}`: take inputs, run code ( and return )

  ```js
  const sayHello = () => {
    console.log("hello");
    console.log(2 - 1);
    console.log("bonjour");
    return "hi";
  };
  sayHello();
  ```

  output

  ```
  // paste your output here


  ```

  `() => ()` take inputs, modify return

  ```js
  const square = (x) => x * x;

  const sleep = () => console.log("sleeping");

  console.log(square(12));
  sleep();
  ```

  output

  ```
  // paste your output here


  ```

# `Loops`

- ## For Loop

  ```js
  for (let i = 0; i < 10; i++) {
    console.log(i);
  }
  ```

  output

  ```
  // paste your output here


  ```

- ## Array.map()

  ```js
  const numbers = [1, 2, 3, 4, 5];
  const doubledNumbers = numbers.map((number) => {
    return number * 2;
  });
  console.log(doubledNumbers);
  ```

  output

  ```
  // paste your output here


  ```

- ## [More Here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)

# `Others`

## Operators

>     strict means that types also need to be the same

- `+` => add
- `-` => subtract
- `*` => multiply
- `/` => divide
- `%` => modulo
- `++` => increment
- `--` => decrement
- `==` => equal
- `!=` => not equal
- `===` => strict equal
- `!==` => strict not equal
- `<` => less than
- `>` => greater than
- `<=` => less than or equal
- `>=` => greater than or equal
- `&&` => and
- `||` => or
- `!` => not
- `typeof` => check data type
- `in` => check if a value is in an array
- `delete` => delete a property

## Conditionals

- `if` => if statement

### Examples

```js
if (age < 18) {
  console.log("you are not old enough");
} else {
  console.log("you are old enough");
}
```

- `else` => else statement
- `switch` => switch statement
- `case` => case statement
- `default` => default case

# Primitive?

## Objects

- `Object` => create an object
- `new` => create an object
- `Object.keys` => get object keys
- `Object.number` => `1`

## Math

- `Math.random` => random number
- `Math.floor` => round down
- `Math.ceil` => round up
- `Math.round` => round to nearest

## JSON

- `JSON.stringify` => convert to JSON
- `JSON.parse` => convert from JSON

## Expressions vs Statements

- `expression` => a value that has a value
- `statement` => a command that uses a value

### [Read Here](https://medium.com/launch-school/javascript-expressions-and-statements-4d32ac9c0e74)

## Ternary Operator

uses like if, but is an expression

- ## Usage

  ```js
  const age = 25;
  const isOld = age > 18 ? "old" : "young";
  console.log(isOld);
  ```

  output

  ```
  // paste your output here


  ```

  - ## Exercise

    explain how the ternary operator works

    output

  ```
  // paste your output here


  ```

# `axios`

- ## What

  _axios is a library that makes http requests_

  > axios is a promise based library
  > axios is a library that makes http requests

- ## Usage

  ```js
  axios.get("https://jsonplaceholder.typicode.com/users").then((res) => {
    console.log(res.data);
  });
  ```

  output

  ```
  // paste your output here

  ```
