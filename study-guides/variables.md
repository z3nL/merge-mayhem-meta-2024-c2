# Variables
- `var`: Variables defined by a `var` declaration are typically declared *outside* of a function and act as global variables. They can be accessed by any function, redefined, and their value may change at any point in the program flow.
- `let`: Variables defined by `let` declaration are typically defined *inside* of a block of code (typically defined by curly brackets, `{}`). This block of code is sometimes called **scope**. Within its scope, a `let` variable's value may change but cannot be redefined. This ensures that a `let` variable name must be unique within a single scope. `let` variables are typically used within functions for temporarily used and are not called in multiple functions like `var` variables.
- `const`: Variables defined by `const` declaration are **constant** values. They cannot be updated or re-declared.

When storing DOM variables, take a moment to think about which type of variable you would use to store DOM references to HTML elements.

**You should use the `const` variable type!** We don't want to be able to redefine or change the variable holding the reference to our HTML elements. This is why we should choose the `const` variable type.

Let's look at an example using the `querySelector` method.
