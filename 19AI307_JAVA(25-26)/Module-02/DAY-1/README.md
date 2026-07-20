# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:
Create a class Car with attributes brand, model, year. Create 2 objects and print their details.

## AIM:
To create a class Car with attributes brand, model, and year, create two objects of the class, and print their details.

## ALGORITHM :
1. Start the program.
2. Create a class named Car with three attributes: brand, model, and year.
3. Inside the class, create a constructor to initialize these attributes.
4. In the main method, create two objects of the Car class.
5. Assign values to the attributes through the constructor.
6. Print the details of both car objects.
7. End the program.


## PROGRAM:
 ```
/*
Program to implement a Class and Objects using Java
Developed by: Rithish R
RegisterNumber:  212224040278
*/
```

## SOURCE CODE:
```java
class Car{
    String brand;
    String model;
    int year;
}
public class prog {
    public static void main(String[] args) {
        Car car1 = new Car();
        car1.brand = "Toyota";
        car1.model = "Innova";
        car1.year = 2022;

        Car car2 = new Car();
        car2.brand = "Hyundai";
        car2.model = "i20";
        car2.year = 2021;

        System.out.println("Car 1: " + car1.brand + " " + car1.model + " " + car1.year);
        System.out.println("Car 2: " + car2.brand + " " + car2.model + " " + car2.year);
    }
}

```

## OUTPUT:
<img width="1264" height="157" alt="image" src="https://github.com/user-attachments/assets/d31687f3-3a6d-4312-95fa-c64d901869e4" />



## RESULT:
The program was executed successfully.
Two car objects were created with the given details.

