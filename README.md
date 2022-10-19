# dz
// Напишите программу, которая на вход принимает два числа и выдает, какое число большее, какое меньшее
// а = 5; b = 7 -> max = 7
// a = 2 b = 10 -> max = 10
// a = -9 b = -3 max = -3


Console.WriteLine("Введите два числа");
int number_1 = Convert.ToInt32(Console.ReadLine());
int number_2 = Convert.ToInt32(Console.ReadLine());
if(number_1 > number_2)
{
    Console.WriteLine("{0} наибольшое число", number_1);
}
else
{
    Console.WriteLine("{0} Наибольшое число", number_2);
}
if(number_1 < number_2)
{
    Console.WriteLine("{0} наименьшее число", number_1);
}
else
{
    Console.WriteLine("{0} наименьшее число", number_2);
}
Console.WriteLine();
dz2
// Напишите программу, которая принимает на вход три числа и выдает максимальное из этих чисел.
// 2,3,7 -> 7
// 44 5 78 ->78
// 22 3 9 ->22


Console.WriteLine("Введите числа");
int number_1 = Convert.ToInt32(Console.ReadLine());

Console.WriteLine("Введите число");
int number_2 = Convert.ToInt32(Console.ReadLine());
Console.WriteLine("Введите число");
int number_3 = Convert.ToInt32(Console.ReadLine());



if(number_1 > number_2)
{
    if(number_1 > number_3)
    {
        Console.WriteLine("Максимальное числа" + number_1);
    }
    else
    {
        Console.WriteLine("Максимальное число: " + number_3);
    }
}
else if (number_2 > number_3)
{
    Console.WriteLine("Максимальное значения: " + number_2);
}
else
{
    Console.WriteLine("Максимальное значение: " + number_3);
}

дз3
Напишите программу, которая на вход принимает число и выдает, является ли число четным 

Console.Write("Введите число: ");
int number_1 = Convert.ToInt32(Console.ReadLine());
if(number_1 % 2 == 0)
{
    Console.WriteLine("четное число");
    Console.WriteLine();
}
else
{
    Console.WriteLine("Нечетное число");
    Console.WriteLine();
}
дз4
// Напишите программу, которая на вход принимает одно число (N) , а на выходе показывает все целые числа в промежутке от -N до N.
// 4 -> "-4, -3, -2, -1, 0, 1, 2, 3, 4"
// 2 -> "-2, -1, 0, 1, 2"


Console.WriteLine("Введите число");
int number_1 = Convert.ToInt32(Console.ReadLine());
int NumberNeg = 2;

while(NumberNeg<=number_1)
if(NumberNeg % 2 == 0)
{
    Console.WriteLine(NumberNeg*1);
    NumberNeg+=2;
}
