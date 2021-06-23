using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp36
{
    class Program
    {
        static void Main(string[] args)
        {
            int age, ageH, ageD, ageM;
            Console.WriteLine("Enter your age");
            age = int.Parse(Console.ReadLine());
            ageD = age * 365;
            ageM = age * 12;
            ageH = ageD * 24;
            //----------------------------------------
            Console.WriteLine("your ageM {0,-10}months",ageM);
            Console.WriteLine("your ageD {0,-10}Day", ageD);
            Console.WriteLine("your ageH {0,-10}hours", ageH);



            Console.ReadKey();
        }
    }
}
