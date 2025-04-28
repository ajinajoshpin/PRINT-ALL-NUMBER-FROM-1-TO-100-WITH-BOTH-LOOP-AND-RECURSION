# PRINT-ALL-NUMBER-FROM-1-TO-100-WITH-BOTH-LOOP-AND-RECURSION
# AIM:
To write a Java program to print numbers from 1 to 100 using both loop and recursion.
# ALGORITHM:
Start the program.
Inside the main() method:
Use a for loop to print numbers from 1 to 100.
Print a separator line (e.g., "Recursion").
Call the recursive method hund(1).
Define the method hund(int count):
If count > 100, stop (base case).
Else, print count and call hund(count+1).
End the program.
# JAVA PROGRAM:
```
// Program to print numbers from 1 to 100 using both loop and recursion
public class loopRec {
    public static void main(String[] args) {
        // Using for loop
        for (int i = 1; i <= 100; i++) {
            System.out.print(i + " ");
        }
        System.out.println("\n");

        System.out.println("Recursion:");

        // Using recursion
        hund(1);
    }

    public static void hund(int count) {
        if (count > 100)
            return;

        System.out.print(count + " ");
        hund(count + 1);
    }
}

```
# OUTPUT:
![image](https://github.com/user-attachments/assets/d10e0855-17be-4b03-bcaf-e77caff49e31)

# RESULT:
The Java program to print numbers from 1 to 100 using both loop and recursion was successfully compiled and executed.
