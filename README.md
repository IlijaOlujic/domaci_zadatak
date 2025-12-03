# Домаћи задатак из Техничке документације 
## Задатак 
Програм који на основу унетих дужина дијагонала ромба d1 и d2 и странице a 
израчунава висину h.
$h = \frac{d_1 \cdot d_2}{2a}$
### Алгоритамска шема
<img width="197" height="488" alt="flowgorithm" src="https://github.com/user-attachments/assets/11e4ad76-ea16-4177-a362-015a59ce3875" />

## Решење

``` csharp

using System;
class Program
{
    static void Main()
    {
        double d1, d2, a, h;
        Console.Write("Unesi d1: ");
        d1 = double.Parse(Console.ReadLine());
        Console.Write("Unesi d2: ");
        d2 = double.Parse(Console.ReadLine());
        Console.Write("Unesi a: ");
        a = double.Parse(Console.ReadLine());
        h = (d1 * d2) / (2 * a);
        Console.WriteLine("h = " + h);
    }
}

```

#Тест примери 

``` csharp

Unesi d1: 6
Unesi d2: 8
Unesi a: 2
h = 12

C:\Users\Olujic PC\source\repos\ConsoleApp15\ConsoleApp15\bin\Debug\ConsoleApp15.exe (process 25200) exited with code 0 (0x0).
To automatically close the console when debugging stops, enable Tools->Options->Debugging->Automatically close the console when debugging stops.
Press any key to close this window . . .

```


``` csharp

Unesi d1: 10
Unesi d2: 20
Unesi a: 4
h = 25

C:\Users\Olujic PC\source\repos\ConsoleApp15\ConsoleApp15\bin\Debug\ConsoleApp15.exe (process 8568) exited with code 0 (0x0).
To automatically close the console when debugging stops, enable Tools->Options->Debugging->Automatically close the console when debugging stops.
Press any key to close this window . . .

```
