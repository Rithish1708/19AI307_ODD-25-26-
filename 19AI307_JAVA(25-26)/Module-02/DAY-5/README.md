# Ex.No:2(E) ACCESS MODIFIERS

## QUESTION:
Create a class Calculator with: One non-static method add(int a, int b) that returns the sum, One static method info() that says "Calculator is ready".

## AIM:
To create a class Calculator containing:
A non-static method add(int a, int b) that returns the sum.
A static method info() that displays the message "Calculator is ready".

## ALGORITHM :
1. Start the program.
2. Create a class named Calculator.
3. Define a non-static method add(int a, int b) that returns the sum of two integers.
4. Define a static method info() that prints "Calculator is ready".
5. In the main method, call the static method using the class name.
6. Create an object of the Calculator class.
7. Call the add() method using the object to compute and display the sum.

## PROGRAM:
 ```
/*
Program to implement a Access Modifiers using Java
Developed by: Rithish R
RegisterNumber:  212224040278
*/
```

## SOURCE CODE:

```java
import java.util.Scanner;

class Calculator {
    int add(int a,int b){
        return (a+b);
    }
    static void info(){
        System.out.println("Calculator is ready");
    }
}

class prog {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int a = input.nextInt();
        int b = input.nextInt();
        Calculator obj = new Calculator();
        Calculator.info();
        System.out.println("Sum: "+obj.add(a,b));
    }
}
```





## OUTPUT:
<img width="1262" height="279" alt="image" src="https://github.com/user-attachments/assets/034162a4-2330-4859-9378-5fbfc443cbca" />



## RESULT:
The program was executed successfully.
The static method displayed the message "Calculator is ready".
After entering two numbers, the non-static method calculated their sum and printed it correctly.
