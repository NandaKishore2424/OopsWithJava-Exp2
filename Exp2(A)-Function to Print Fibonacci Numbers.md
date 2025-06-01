# EX.NO 2(A): Function to Print Fibonacci Numbers
## DATE:
## Name: Nanda Kishore R
## Reg.no: 212222060157

## AIM:
To write a Java program that prints the Fibonacci series up to the Nth term using a function.

## Algorithm:

1. Create a class named welcometomyid.

2. Define a static method Fibonacci(int N) to generate and print Fibonacci numbers up to the Nth term.

3. Inside the method, initialize two integer variables, num1 as 0 and num2 as 1.

4. Use a while loop to iterate until the counter reaches N.

5. In each iteration, print the current Fibonacci number (num1), calculate the next term as the sum of the previous two numbers, and update the variables accordingly.

6. In the main() method:

    > Use the Scanner class to read the value of N from the user.

    > Call the Fibonacci(N) method to display the Fibonacci series.

## Program:

```
import java.util.*;
public class welcometomyid{
    static void Fibonacci(int N)
    {
        int num1=0,num2=1;
        int counter=0;
        while(counter<N){
            System.out.print(num1+" ");
            int num3=num2+num1;
            num1=num2;
            num2=num3;
            counter=counter+1;
        }
    }
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int N=sc.nextInt();
        Fibonacci(N);
    }
}
```

## Output:
![image](https://github.com/user-attachments/assets/2b3db5b9-1eb4-411f-b377-388faf588bea)


## Result:
Thus, the Java program to display the Fibonacci series up to the Nth term using a function is implemented successfully.
