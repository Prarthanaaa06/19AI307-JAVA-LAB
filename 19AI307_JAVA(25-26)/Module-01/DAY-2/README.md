# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
In a magical building, an elevator behaves oddly:

If the floor number is divisible by 3 and 5, it says "Skipped".

If the floor number is divisible by 3 only, it says "Beware!".

If the floor number is divisible by 5 only, it says "Blessings!".

Otherwise, it announces the floor number - print - "Floor {number}" .

## AIM:

Write a Java program to simulate this elevator logic for a given floor number.

## ALGORITHM :
1.	Start the program.
   
2.	Import the necessary package 'java.util'
   
3.	Read the floor number n from the user.
   
4. Check if n is divisible by both 3 and 5 (n % 3 == 0 && n % 5 == 0):

5. If true, print "Skipped".

6. Else, check if n is divisible only by 3 (n % 3 == 0):

7. If true, print "Beware!".

8. Else, check if n is divisible only by 5 (n % 5 == 0):

9. If true, print "Blessings!".

10. Otherwise, print "Floor " + n.

11. Stop the program.



## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by: PRARTHANA D
RegisterNumber:  212225230213
*/
```

## SOURCE CODE:
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args){
        Scanner s = new Scanner(System.in);
        int n = s.nextInt();
        if (n%3==0 && n%5==0){
            System.out.println("Skipped");
        }
        else if (n%3==0){
            System.out.println("Beware!");
        }
        else if (n%5==0){
            System.out.println("Blessings!");
        }
        else {
            System.out.println("Floor "+n);
        }
    }
}
```

## OUTPUT:

<img width="1077" height="865" alt="image" src="https://github.com/user-attachments/assets/630d53e9-0553-4375-979c-d923e319c45e" />


## RESULT:

Thus, the Java program to simulate the magical elevator logic using conditional statements was executed successfully, and the expected output was obtained.
