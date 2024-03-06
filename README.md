# Exp02-CSharpPattern
# Aim:
To write the C# program to print Pascal's triangle.

# Algorithm:
# Step1:
Initialize the neccessary attributes.

# Step2:
Get the no. of rows from the user.

# Step3:
Using for loop print the rows, columns and spaces at required places.

# Step4:
Apply if condition to print 1.

# Step5:
If the condition fails, print the number using the formula. value=value*(i-j+1)/j.

# Program:
```
DEVELOPED BY : VAISHNAVI S
REG NO : 212222230165
```
```
using System;
public class Pattern {
   class Example {
      public static void Main() {
         int rows, c = 1, s, i, j;
         rows=Convert.ToInt32(Console.ReadLine());
         Console.WriteLine("Pascal's triangle");
         for(i = 0; i<rows; i++) {
            for(s = 1; s <= rows-i; s++)
            Console.Write(" ");
            for(j = 0; j <= i; j++) {
               if (j == 0||i == 0)
               c = 1;
               else
               c = c*(i-j+1)/j;
               Console.Write(c + " ");
            }
            Console.WriteLine();
         }
      }
   }
}
```
# Output:
![Screenshot 2024-03-06 224403](https://github.com/Vaishnavi-saravanan/Exp02-CSharpPattern/assets/118541897/d6b4eab5-fdd2-444a-886e-23f4121d9a00)
![Screenshot 2024-03-06 224333](https://github.com/Vaishnavi-saravanan/Exp02-CSharpPattern/assets/118541897/4580a507-d69e-4c89-ab7a-5b580522ee2b)

# Result:
Hence, a C# program for a pascal's triangle is executed successfully.
