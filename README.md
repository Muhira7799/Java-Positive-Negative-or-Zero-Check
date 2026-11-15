# Java Positive, Negative, or Zero Check

A small Java console program that reads an integer from the user and tells whether it is positive, negative, or zero.

## What It Demonstrates

- Reading input with `Scanner`
- An `if / else if / else` chain with three outcomes

```java
if (number > 0) {
    System.out.println("The number is positive.");
} else if (number < 0) {
    System.out.println("The number is negative.");
} else {
    System.out.println("The number is zero.");
}
```

## Sample Runs

```
Enter a number: 8
The number is positive.
```

```
Enter a number: -3
The number is negative.
```

```
Enter a number: 0
The number is zero.
```

## Requirements

- Java Development Kit (JDK) 8 or higher

## Getting Started

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
javac PositiveNegative.java
java PositiveNegative
```

## Notes

- Entering something that is not a whole number, such as `2.5` or `abc`, throws an `InputMismatchException`.

## Project Structure

```
.
├── PositiveNegative.java
└── README.md
```

## Possible Improvements

- Handle invalid input with `hasNextInt()` or `try-catch`
- Use `double` to accept decimal numbers
- Keep asking for numbers until the user quits
