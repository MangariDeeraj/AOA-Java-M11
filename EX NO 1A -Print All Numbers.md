
# EX 1A Print All Numbers 
## DATE: 08-09-2026
## AIM:
To Write a Java program that takes an integer input N from the user and prints all the numbers from 1 to N, separated by spaces, on a single line..

## Algorithm
1. Start

2.Input an integer N from the user.

3.Initialize a counter variable i = 1.

4.Repeat while i ≤ N:

5.Print i followed by a space.

6.Increment i by 1.
 

## Program:
```
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter an integer N: ");
        int N = scanner.nextInt();

        for (int i = 1; i <= N; i++) {
            System.out.print(i);
            if (i < N) System.out.print(" ");
        }

        scanner.close();
    }
}

```

## Output:
<img width="476" height="162" alt="image" src="https://github.com/user-attachments/assets/0ede43d7-7a8e-45e5-98ab-c1d2c7e1e4b3" />


## Result:
The program successfully print all the numbers from 1 to N.




## Result:
The program successfully print all the numbers from 1 to N. 
