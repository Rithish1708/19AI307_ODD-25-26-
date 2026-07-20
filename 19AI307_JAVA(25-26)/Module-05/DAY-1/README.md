# Ex.No:5(A) INPUTSTREAMREADER 

## QUESTION:
Write a program to read user input from the keyboard using InputStreamReader 

## AIM:
To write a Java program that reads a string (username) from the keyboard using InputStreamReader, converts byte input into characters, and displays a greeting message.

## ALGORITHM :
1. Start the program.
2. Create an InputStreamReader object to read bytes from System.in.
3. Wrap it inside a BufferedReader to read input efficiently.
4. Ask the user to enter their name.
5. Read the input string using readLine().
6. Print “Hello, <name>!”.
7. End the program.

## PROGRAM:
 ```
/*
Program to implement a InputStreamReader using Java
Developed by: Rithish R
RegisterNumber:  212224040278
*/
```

## SOURCE CODE:

```java
import java.util.Scanner;
import java.io.InputStreamReader;
import java.io.BufferedReader;
import java.io.IOException;

public class Main{
    public static void main(String[] args){
        try(BufferedReader bf = new BufferedReader(new InputStreamReader(System.in))){
            String input = bf.readLine();
            System.out.print("Hello, " + input + "!");
        }
        catch(IOException e){
            System.out.println(e.getMessage());
        }
    }
}
```


## OUTPUT:
<img width="1216" height="180" alt="image" src="https://github.com/user-attachments/assets/b407d69b-97cb-4fc1-bc41-a6a008ef9a1c" />



## RESULT:
When the user enters Manoj as input, the program reads the name using InputStreamReader and displays the message:

“Hello, Manoj!”
