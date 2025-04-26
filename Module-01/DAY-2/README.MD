# Ex.No:1(B) VARIABLES AND OPERATOR

## AIM:
To write a Java program to swap the values of the two variables by using a third variable. 
## ALGORITHM :
```
1.Start
2.Declare three integer variables: a, b, and temp.
3.Prompt the user to enter values for a and b.
4.Read the values of a and b using Scanner.
5.Store a in temp (temp = a).
6.Assign b to a (a = b).
7.Assign temp to b (b = temp).
8.Display the swapped values of a and b.
```
## PROGRAM:
 ```
/*
Program to implement a variable and operators using Java
Developed by: v.sreeja
RegisterNumber:  212222230169
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Demo
{
    public static void main(String[] args){
    Scanner sc=new Scanner(System.in);
    int a = sc.nextInt();
    int b = sc.nextInt();
    int temp;
    temp=a;
    a=b;
    b=temp;
    System.out.println("After swapping a= "+a +" b="+b);
    }
}
```
## OUTPUT:




## RESULT:
Thus, the Java program the values are successfully swapped, and the output displays: "a = 20" and "b = 10".
