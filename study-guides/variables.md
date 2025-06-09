## Variables

In order to save the DOM references to your HTML elements, you must store them in variables.

Let's breakdown the syntax to **declare a variable** in JavaScript.

```javascript
var varName = value;
```

- `var`: This keyword defines a variable. There are three types of variables that were introduced with the [ES6 JavaScript revision](http://es6-features.org/#Constants). To declare a variable, developers may now define a variable as `var`, `const`, and `let`. We will explain in more detail below the difference between these variable types.
- `varName`: Name of your variable.
- `=`: Similar to most programming languages, the `=` symbol is used to define and set a variable name to a specific value.
- `;`: All JavaScript lines of code and statements must end with a semicolon `;`.

To define an empty variable, just define the type of variable and name, and end with a semicolon (e.g `var varName`).

#### `var`, `let`, and `const`

In some programming languages, like Java and C++, when declaring a variable you must specify the data type (integer, String, float, boolean, etc.) In JavaScript, a variable does not need to be specifically defined in its declaration. Instead, the keyword `var`, `const`, and `let` define how a variable can be used and/or changed.

- `var`: Variables defined by a `var` declaration are typically declared *outside* of a function and act as global variables. They can be accessed by any function, redefined, and their value may change at any point in the program flow.
- `let`: Variables defined by `let` declaration are typically defined *inside* of a block of code (typically defined by curly brackets, `{}`). This block of code is sometimes called **scope**. Within its scope, a `let` variable's value may change but cannot be redefined. This ensures that a `let` variable name must be unique within a single scope. `let` variables are typically used within functions for temporarily used and are not called in multiple functions like `var` variables.
- `const`: Variables defined by `const` declaration are **constant** values. They cannot be updated or re-declared.

When storing DOM variables, take a moment to think about which type of variable you would use to store DOM references to HTML elements.

**You should use the `const` variable type!** We don't want to be able to redefine or change the variable holding the reference to our HTML elements. This is why we should choose the `const` variable type.

Let's look at an example using the `querySelector` method.
