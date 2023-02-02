using System;
using System.Collections.Generic;
using System.Globalization;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Informe um numero");
            int numero =  int.Parse(Console.ReadLine());
            int resultado = numero * 9;
            Console.WriteLine(resultado.ToString());
            
            

            Console.ReadKey();

            
        }
    }
}
