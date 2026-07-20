# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:
Write a Java program to calculate the factorial of a number using a for loop. The factorial of n is the product of all positive integers less than or equal to n.



## AIM:

To write a Java program to calculate the factorial of a given number using a for loop.

## ALGORITHM :
1. Start the program.
2. Read an integer n from the user.
3. Initialize a variable fact to 1.
4. Use a for loop that runs from 1 to n.
5. In each iteration, multiply fact by the loop variable.
6. After the loop ends, fact contains the factorial of n.
7. Display the factorial result on the screen.





## PROGRAM:
 ```
/*
Program to implement a Looping Statement using Java
Developed by: Rithish R
RegisterNumber:  212224040278
*/
```

## SOURCE CODE:
```java
import java.util.Scanner;
public class Main{
    public static void main(String[] args){
        Scanner input=new Scanner(System.in);
        int n=input.nextInt();
        int res=1;
        for(int i=1;i<=n;i++){
            res*=i;
        }
        System.out.print("Factorial of "+n+" is: "+res);
    }
}
```






## OUTPUT:

<img width="1264" height="219" alt="image" src="https://github.com/user-attachments/assets/14f7a12e-2988-4a39-b8a2-01fb08b3c811" />



## RESULT:
The program was executed successfully.
When the input 0 was entered, the loop executed correctly and returned the value 1.
