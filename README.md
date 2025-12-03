# Домаћи задатак из Техничке документације 
## Задатак 
Програм који на основу унетих дужина дијагонала ромба d1 и d2 и странице a 
израчунава висину h.
$h = \frac{d_1 \cdot d_2}{2a}$
### Алгоритамска шема
<img width="197" height="488" alt="flowgorithm" src="https://github.com/user-attachments/assets/11e4ad76-ea16-4177-a362-015a59ce3875" />

## Решење

'''csharp






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



'''
