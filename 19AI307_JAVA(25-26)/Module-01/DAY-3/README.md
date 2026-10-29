# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:
Write a Java program that asks the user to enter how many terms of the Fibonacci series they want to display.

Use a for loop to generate the series.

The first two terms should always be 0 and 1.

From the third term onwards, each term should be calculated as the sum of the previous two terms.

Display the series in a clear and readable format.

## AIM:
The Fibonacci series is a sequence of numbers in which each number is the sum of the two preceding ones. The series starts with 0 and 1. Therefore, the beginning of the series looks like this:

0, 1, 1, 2, 3, 5, 8, 13, ...

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	





## PROGRAM:
 ```
/*
Program to implement a Looping Statement using Java
Developed by: Prarthana D
RegisterNumber:  212225230213
*/
```

## SOURCE CODE:

```
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner s = new Scanner(System.in);
        int n = s.nextInt();
        
        int term1 = 0;
        int term2 = 1;
        System.out.print("Fibonacci Series: "+term1 +" " +term2 + " ");
        
        for (int i=1;i<n-1;i++){
            int next = term1+ term2; 
            System.out.print(+next +" ");
            term1 = term2;
            term2 = next ;
        }
    }
}
```

## OUTPUT:

<img width="1227" height="675" alt="image" src="https://github.com/user-attachments/assets/2300bf5b-721d-44a3-9937-094bf5549958" />


## RESULT:
