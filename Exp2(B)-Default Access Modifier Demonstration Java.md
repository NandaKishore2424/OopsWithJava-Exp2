# EX.NO 2(B): Default Access Modifier Demonstration Java

## DATE:
## Name: Nanda Kishore R
## Reg.no: 212222060157

## AIM:
To write a Java program demonstrating the default access modifier by using two classes and printing the sum of two numbers.

## Algorithm:

1. Create a class named BaseClass.

2. In this class, declare two integer variables a and b, and initialize them to 3 and 5, respectively.

3. Define a default-access method named display() that calculates the sum of a and b and prints the result.

4. Create another class named Main with the main() method.

5. In the main() method, create an object of BaseClass.

6. Call the display() method of the BaseClass object to print the sum.

## Program:

```
class BaseClass {
    int a = 3;
    int b = 5;

    void display() {
        int c = a + b;
        System.out.println(c);
    }
}

public class Main {
    public static void main(String[] args) {
        BaseClass obj = new BaseClass();
        obj.display();
    }
}

```

## Output:
![image](https://github.com/user-attachments/assets/629ab97a-7d0e-4686-95c8-2f9d36e9fc0e)


## Result:
Thus, the Java program to demonstrate the default access modifier and print the sum of two variables using two classes is implemented successfully.
