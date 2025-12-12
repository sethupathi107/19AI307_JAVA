# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Student' with String variable 'name' and String variable 'address'.

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
Developed by: SETHUPATHI K
RegisterNumber:  212223040189
*/
```

## Sourcecode.java:
``` JAVA
class Student {
    String name = "John";
    String address = "Chennai";
}

class Test {
    public static void main(String[] args) {
        Student obj = new Student();

        System.out.println("Name: " + obj.name);
        System.out.println("Address: " + obj.address);
    }
}

```


## OUTPUT:
<img width="167" height="197" alt="Screenshot 2025-11-20 221823" src="https://github.com/user-attachments/assets/d00e5571-3926-4609-996d-1d16c2e8461f" />



## RESULT:

Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.

