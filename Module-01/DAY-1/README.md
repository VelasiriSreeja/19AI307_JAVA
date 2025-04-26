# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a main() for the class named 'Test' to access class 'date' and display in-date of an employee(Time be in format Day:month:year)
## ALGORITHM :
1.	Start the program.Start
2.Define a class named date with three data members: day, month, and year.
3.Create a method inside date class to set the date values (e.g., setDate() or constructor).
4.Create a method inside date class to display the date in the format Day:Month:Year.
5.Define a class named Test which contains the main() method.
6.Inside main() method, create an object of the date class.
7.Use the object to set and display the in-date of the employee.
8.	End

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
