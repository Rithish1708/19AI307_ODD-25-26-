# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
Write a Java program to reverse a given string.


## AIM:
To write a Java program that reads a string from the user and prints the reversed string.

## ALGORITHM :
1. Start the program.
2. Read a string input from the user.
3. Create an empty string variable to store the reversed string.
4. Use a loop to traverse the string from the last character to the first.
5. Append each character to the reversed string.
6. After the loop ends, the reversed string is ready.
7. Display the reversed string to the user.


## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
Developed by: Rithish R
RegisterNumber:  212224040278
*/
```

## SOURCE CODE:

```java
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner input=new Scanner(System.in);
        String str=input.nextLine();
        String rev="";
        for(int i=str.length()-1;i>=0;i--){
            rev+=str.charAt(i);
        }
        System.out.print("Reversed string: "+rev);
    }
}
```





## OUTPUT:

<img width="1262" height="218" alt="image" src="https://github.com/user-attachments/assets/6a8cd4eb-e9d4-46fb-a5bc-a9b6ed711ce4" />


## RESULT:
The program was executed successfully.
When the input "welcome" was entered, the program reversed the characters correctly.
