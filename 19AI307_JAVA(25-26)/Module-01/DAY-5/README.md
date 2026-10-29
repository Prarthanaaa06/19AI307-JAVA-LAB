# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:

Write a java program to find the longest word in a sentence.

## AIM:
Write a java program to find the longest word in a sentence.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	





## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
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
        if (s.hasNextLine()){
            String sen = s.nextLine();
            String[] words = sen.split(" ");
            String longest = "";
            
            for (String word : words){
                if (word.length()> longest.length()){
                    longest = word;
                }
            }
            System.out.println("The longest word is: "+longest);
        }
    }
}
```

## OUTPUT:

<img width="1232" height="660" alt="image" src="https://github.com/user-attachments/assets/7f57b378-3f66-462e-9c9b-757f592f46a8" />


## RESULT:
