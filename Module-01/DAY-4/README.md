# Ex.No:1(D) USER DEFINED METHOD.

## AIM:
To create a Java program print a program to find out two numbers are given or not using method.

## ALGORITHM :
1.Start the program
2.Create a class named NumberCheck.
3.Inside the class, define a method checkNumbers(Integer a, Integer b).
4.In the method, check if both a and b are not null (i.e., they are given).
5.If both are given, print "Both numbers are given: a and b".
6.If either is missing, print "One or both numbers are not given."
7.In another class (like Main), define the main() method.
8.End of program

## PROGRAM:
 ```
/*
Program to implement a User Defined Method using Java
Developed by: v.sreeja
RegisterNumber: 212222230169 
*/
```

## Sourcecode.java:
```
public void check()
{
    Scanner scan=new Scanner(System.in);
    n=scan.nextInt();
    m=scan.nextInt();
    if(n==m)
    {
        System.out.print("Same");
    }
    else
    {
        System.out.print("Not Same");
    }
}
```

## OUTPUT:

![Screenshot 2025-04-26 151252](https://github.com/user-attachments/assets/0e8d9946-95f5-41f1-a979-9f677a121e10)



## RESULT:
Thus, the Java program to find out two numbers are given or not using method was done successfully.

