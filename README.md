# Simple Essentials (SE)

The `SE` class provides utility methods for common tasks in Java programming. Whether you’re a beginner or an experienced developer, these methods can simplify your code and enhance readability.

## Methods

### `nL()` and `nL(int c)`:

- `nL()`: Prints a single newline character.
- `nL(int c)`: Prints multiple newlines based on the integer argument.

### `randI(int min, int max)`:

Generates a random integer between the specified minimum and maximum values (inclusive).

### `randD(double min, double max)`:

Generates a random double between the specified minimum and maximum values (exclusive).

### `print(String toPrint)`, `print(int i)`, and `print(double d)`:

Overloaded methods to print strings, integers, and doubles followed by a newline.

### `printN(String toPrint)`, `printN(int i)`, and `printN(double d)`:

Similar to the previous methods, but without starting a new line.

## Usage

### Printing Newlines:

```java
SE.nL();   // Prints a single newline
SE.nL(3);  // Prints three newlines
```
### Generating Random Numbers:
```
int randomInt = SE.randI(1, 100);                 // Generates a random integer between 1 and 100
double randomDouble = SE.randD(0.0, 1.0);         // Generates a random double between 0.0 (inclusive) and 1.0 (exclusive)
```
### Printing with Convenience:
```
SE.print("Hello, World!");  // Prints "Hello, World!" followed by a newline
SE.printN("Count: ");        // Prints "Count: " without a newline
SE.print(42);                // Prints the integer 42 followed by a newline
```
