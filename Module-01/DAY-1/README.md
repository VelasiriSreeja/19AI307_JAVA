# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a main() for the class named 'Test' to access class 'date' and display in-date of an employee(Time be in format Day:month:year)
## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a String variable 'address' and initialize it with the value "Chennai"
5.	Define a class named 'Test'
6.	Define the 'main' method within the 'Test' class
7.	Create an object 'obj' of the 'Student' class
8.	Print the value of 'name' and 'address' variables of the 'obj' object
9.	End

## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: v.sreeja
RegisterNumber:  212222230169
*/
```

## Sourcecode.java:
```
public class Test{
    public static void main(String[] args)
    {
         Scanner scanner = new Scanner(System.in);
        Date in=new Date();
        int day,month,year;
        in.day = scanner.nextInt();

        in.month = scanner.nextInt();
 
        in.year = scanner.nextInt();
        String hour=String.format("%d",in.day);
        String min=String.format("%d",in.month);
        String secs=String.format("%d",in.year);
        
        System.out.println(hour+"/"+min+"/"+secs);
       
    }
}

```


## OUTPUT:

![Screenshot 2025-04-26 142842](https://github.com/user-attachments/assets/f0f00131-baa4-4f9a-bb72-9d7c0f8a086a)



## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.
