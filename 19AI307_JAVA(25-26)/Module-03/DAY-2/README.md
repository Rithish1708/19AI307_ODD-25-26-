# Ex.No:3(b) POLYMORPHISM

## QUESTION:
Write a Java program that calculates the area of different shapes using method overloading. Create a class AreaCalculator with:

area(int side) for square

area(int length, int breadth) for rectangle

area(double radius) for circle



## AIM:

To write a Java program that calculates the area of different shapes (square, rectangle, and circle) using method overloading in a class AreaCalculator.

## ALGORITHM :
1. Start the program.
2. Create a class named AreaCalculator.
3. Overload three methods named area():
  area(int side) → calculates area of a square
  area(int length, int breadth) → calculates area of a rectangle
  area(double radius) → calculates area of a circle
4. In the main method, read values for square, rectangle, and circle.
5. Create an object of AreaCalculator.
6. Call each overloaded method with appropriate arguments.
7. Display the calculated areas.


## PROGRAM:
 ```
/*
Program to implement a Polymorphism using Java
Developed by: Rithish R
RegisterNumber:  212224040278
*/
```

## SOURCE CODE:

```java
import java.util.*;

class AreaCalculator {

    // Square
    int area(int side) {
        return side * side;
    }

    // Rectangle
    int area(int length, int breadth) {
        return length * breadth;
    }

    // Circle
    double area(double radius) {
        return Math.PI * radius * radius;
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        AreaCalculator calc = new AreaCalculator();

        // Square
        int side = sc.nextInt();
        System.out.println("Area of square: " + calc.area(side));

        // Rectangle
        int length = sc.nextInt();
        int breadth = sc.nextInt();
        System.out.println("Area of rectangle: " + calc.area(length, breadth));

        // Circle
        double radius = sc.nextDouble();
        System.out.println("Area of circle: " + calc.area(radius));
    }
}

```





## OUTPUT:

<img width="1259" height="331" alt="image" src="https://github.com/user-attachments/assets/2e8d9c03-61c3-4a03-95a2-7f18a30acbfe" />


## RESULT:
The program was executed successfully.
Using method overloading, the areas of a square, rectangle, and circle were calculated correctly.
