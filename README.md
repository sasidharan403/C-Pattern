# Pattern

## Aim:
To write a C# program for a pascal's triangle.
## Equipment Required:
Microsoft Visual Studio or any C# compiler.
## Algorithm:
## Step 1: 
Initialize the necessary attributes.

## Step 2:
Get the limit from the user.

## Step 3:
using for loop print the rows and columns and space.

## Step 4:
Check the first and last rows of the triange is 1 using if condition.

## Step 5:
Otherwise use else to print the inner value

val = val * (i - j + 1) / j;

## Step 6:
Check the program for any error.

if not.

## Step 7: print the program.
## Program:
~~~
Developed By: sasidharan
Register No: 212221240049
~~~
~~~
using System;
public class Exercise33
{
    public static void Main()
    {
        int rows, c = 1, a, i, j;

        Console.Write("Input number of rows: ");
        rows = Convert.ToInt32(Console.ReadLine());
        for (i = 0; i< rows;i++) {
            for (a = 1; a <= rows - i; a++)
            {
                Console.Write(" ");
            }
            for (j = 0; j <= i; j++)
            {
                if (j == 0 || i == 0)
                {
                    c = 1;
                }
                else
                {
                    c = c * (i - j + 1) / j;
                }
                Console.Write("{0} ", c);
            }
            Console.Write("\n");
        }
    }
}
~~~
## Output:
![image](https://github.com/sasidharan403/C-Pattern/assets/94154712/82b5580a-bfe5-4fe9-bb85-a281ba4d1138)

## Result:
Hence, a C# program for a pascal's triangle is executed successfully.
