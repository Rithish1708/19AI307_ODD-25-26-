# Ex.No:5(E) MULTITHREADING -SYNCHRONIZATION

## QUESTION:
Maintain two int variables a and b, read their initial values from user. Use synchronized block to swap them and print swapped values.


## AIM:
To write a Java program that uses a synchronized block to safely swap two integers read from the user and display the swapped values.

## ALGORITHM :
1. Start the program.
2. Read two integer values a and b from the user.
3. Create a common object for synchronization (e.g., Object lock).
4. Use a synchronized block on the lock object to swap a and b.
5. Print the swapped values of a and b.
6. End the program.

## PROGRAM:
 ```
/*
Program to implement a Synchronization concept using Java
Developed by: Rithish R
RegisterNumber:  212224040278
*/
```

## SOURCE CODE:

```java
import java.util.Scanner;

public class Main {

    private static final Object lock = new Object();

    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        int a = sc.nextInt();
        int b = sc.nextInt();

        // synchronized swap block
        synchronized (lock) {
            int temp = a;
            a = b;
            b = temp;
        }

        System.out.println("a = " + a);
        System.out.println("b = " + b);
    }
}

```





## OUTPUT:
<img width="1260" height="274" alt="image" src="https://github.com/user-attachments/assets/48543f9d-5fe9-4dbc-860e-b215ed60f9b7" />



## RESULT:
When the user enters 5 and 10, the program swaps the two values safely using a synchronized block.
After swapping, the program displays: a = 10 and b = 5.
