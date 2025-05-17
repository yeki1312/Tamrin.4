# Tamrin.4using System;

class Program
{
    static void Main()
    {
        int evenCount = 0; // شمارش اعداد زوج
        int oddCount = 0;  // شمارش اعداد فرد

        Console.WriteLine("لطفاً 10 عدد وارد کنید:");

        for (int i = 1; i <= 10; i++)
        {
            Console.Write($"عدد {i}: ");
            int number = int.Parse(Console.ReadLine());

            if (number % 2 == 0)
                evenCount++;
            else
                oddCount++;
        }

        Console.WriteLine("\nتعداد اعداد زوج: " + evenCount);
        Console.WriteLine("تعداد اعداد فرد: " + oddCount);
    }
}

