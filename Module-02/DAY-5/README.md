# Ex.No:2(E)  SMALLEST ELEMENT IN AN ARRAY

## AIM:
to write a java program to find the largest element in an array and then print the largest value
## ALGORITHM :
```
1. Start the program
2. Create an array with some elements.
3. Assume the first element as the largest.
4. Traverse the array from start to end.
5. Compare each element with the current largest value.
6. If any element is greater, update the largest value.
7. After finishing the loop, print the largest value.
8. End the program


	

## PROGRAM:
 ```
/*
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
        int size=scan.nextInt();
        int[] arr=new int[size];
        int i;
        for(i=0;i<size;i++)
        {
            arr[i]=scan.nextInt();
        }
        int max=arr[0];
        for(i=0;i<size;i++)
        {
            if(arr[i]>max)
            {
                max=arr[i];
            }
        }
        System.out.print("The largest element in the array is: "+max);
    }
}
```


## OUTPUT:

![Screenshot 2025-04-26 153610](https://github.com/user-attachments/assets/493ed988-abac-4576-9107-7cdd129d99a2)




## RESULT:
to write a java program to find the largest element in an array and then print the largest value was executed successfully



