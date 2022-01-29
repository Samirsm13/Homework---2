using System;

namespace ConsoleApp.Homework_2
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int a = 123;

            if (a >= 100 && a < 1000)
                a = a * 1000 + a;
            {
                Console.WriteLine(a);
            }
            
        }
    }
}



