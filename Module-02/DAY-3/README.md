# Ex.No:2(C)    SINGLE ARRAY

## AIM:
To create a java program to read 3 values and display the all 53 values from array using single dimensional array.

## ALGORITHM :
```
1.	Start the program.
2.	2.	Import the `Scanner` class from the `java.util` package
3.	Define a class named `ArrayExample`
4.	Inside the `main` method:
-	a) Create a `Scanner` object called `scanner` to take user input
-	b) Declare an integer array `values` of size 5
-	c) Use a `for` loop to iterate from `i = 0` to `i < 3`:
-   d) Take input from the user and store it in `values[i]`
5.	Print "Elements in Array are :"
6.	Use another `for` loop to iterate from `i = 0` to `i < 3`:
-	a) Print each element in `values` followed by a space
7.	Close the `scanner` to release resources
8.	End

```
## PROGRAM:
 ```
/*
Program to implement a Single Array using Java
Developed by: sreeja
RegisterNumber: 212222230169 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Scanner scan=new Scanner(System.in);
        int[] arr=new int[3];
        for(int i=0;i<3;i++)
        {
            arr[i]=scan.nextInt();
        }
        System.out.println("One dimensional array elements are");
        for(int i=0;i<3;i++)
        {
            System.out.println(arr[i]);
        }
        scan.close();
    }
}
```



## OUTPUT:

![Screenshot 2025-04-26 152849](https://github.com/user-attachments/assets/a379f854-f87b-498e-8935-e551491c73f1)


## RESULT:
Thus, the Java program Thus the java program to read 5 values and display the all 5 values from array using single dimensional  was executed successfully.


