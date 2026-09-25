# Java-Day-08-Positive-Negative-Zero
# Java Day 8 - Positive, Negative or Zero

This program takes a number from the user and checks whether the number is positive, negative, or zero.

## Example Input

```text id="input8"
Enter a number: -15
```

## Output

```text id="output8"
The number is negative.
```

## Conditions

* Number greater than `0` → Positive
* Number less than `0` → Negative
* Number equal to `0` → Zero

## Concepts Used

* Scanner
* User input
* `if` statement
* `else if` statement
* `else` statement
* Comparison operators

## How It Works

1. The program takes a number from the user.
2. It checks if the number is greater than zero.
3. If true, it prints that the number is positive.
4. Otherwise, it checks if the number is less than zero.
5. If both conditions are false, the number must be zero.
6. The result is displayed on the screen.

## Java Code

```java id="code8"
import java.util.Scanner;

public class Main
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int number = sc.nextInt();

        if (number > 0)
        {
            System.out.println("The number is positive.");
        }
        else if (number < 0)
        {
            System.out.println("The number is negative.");
        }
        else
        {
            System.out.println("The number is zero.");
        }

        sc.close();
    }
}
```

## Sample Output

```text id="sample8"
Enter a number: -15
The number is negative.
```

## Goal

The goal of this project is to practice `if-else if-else` statements and comparison operators in Java.
