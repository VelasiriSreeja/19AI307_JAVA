# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:
To create a java program to find the length or size of 2D array.

## ALGORITHM :
```
1. Start
2. Create a 2D array with some values.
3. Find the number of rows using array.length.
4. Find the number of columns using array[0].length.
5. Multiply rows and columns to get the total number of elements.
6. Print the number of rows, columns, and total elements.
7. End
```



## PROGRAM:
 ```
/*
Program to implement a Multi Dimensional Array using Java
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
        int[][] arr = {{50,60},{70,80},{90,10}};
        int i;
        System.out.println("Parent size = "+arr.length);
        for(i=0;i<arr.length;i++)
        {
            System.out.println("Child-"+(i+1)+" size = "+arr[i].length);
        }
    }
}
```

## OUTPUT:

![Screenshot 2025-04-26 153128](https://github.com/user-attachments/assets/11ad06bb-e05f-47cf-a7c9-8c5489f664f5)


## RESULT:
Thus the java program to find the length or size of 2D array was executed successfully.


