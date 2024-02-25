# Exp02-CSharpPattern

## Aim:

## Algorithm:

### Step1: create a class
### Step2: Give the input values
### Step3: use nested for loop
### Step4: Display the output
### Step5: End the program.

## Program:
Developed by: Vinush.CV
Reg no: 212222230176
```c#
using System;

class PascalTriangle
{
    public static void Main()
    {
        Console.Write("Enter the number of rows of Pascal Triangle: ");
        int rows = Convert.ToInt32(Console.ReadLine());

        for (int i = 0; i < rows; i++)
        {
            for (int space = 0; space < rows - i; space++)
            {
                Console.Write(" ");
            }

            int num = 1;
            for (int j = 0; j <= i; j++)
            {
                Console.Write(num + " ");
                num = num * (i - j) / (j + 1);
            }
            Console.WriteLine();
        }
    }
}
```

## Output:
![Screenshot 2024-02-25 232459](https://github.com/vinushcv/Exp02-CSharpPattern/assets/113975318/5bf57a99-2ff4-47da-af68-928a1d5a7b01)


## Result:
Thus the C# program to print the pascal's triangle is executed successfully.

