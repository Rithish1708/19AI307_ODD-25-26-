# Ex.No:5(D) THREAD PRIORITY

## QUESTION:

Write a java program for determine the priority and name of the current thread

## AIM:
To write a Java program that reads a thread name from the user, sets it to the current thread, and displays the thread's name, priority, and full thread details.

## ALGORITHM :
1. Start the program.
2. Create a Scanner object to read user input.
3. Read the thread name from the user.
4. Get the current thread using Thread.currentThread().
5. Set the thread name using setName().
6. Get the thread priority using getPriority().
7. Print the priority, name, and full thread information.
8. End the program.



## PROGRAM:
 ```
/*
Program to implement a Thread Priority Concept using Java
Developed by: Rithish R
RegisterNumber:  212224040278
*/
```

## SOURCE CODE:
```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);
        String newName = sc.nextLine();  // Read thread name from user

        Thread t = Thread.currentThread();  // Get current thread

        t.setName(newName);  // Set new thread name

        // Display results
        System.out.println("Priority of Thread: " + t.getPriority());
        System.out.println("Name of Thread: " + t.getName());
        System.out.println(t);  // Prints in format Thread[name,priority,group]

        sc.close();
    }
}

```






## OUTPUT:

<img width="1269" height="182" alt="image" src="https://github.com/user-attachments/assets/00a08b61-8a28-4d71-9e94-9217d0e9d716" />


## RESULT:

Thus, the program successfully reads, sets, and displays the thread’s name and priority.
