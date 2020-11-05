# c#
console application in c#
using System;

namespace cs_console_calculator
{
    class Program
    {
       
        static void Main(string[] args)
        {
            double firstnum;
            double secnum;
            double Answer;
            string ops;

            Console.WriteLine("console calculator in c#\n");
            Console.WriteLine("Enter first number\n");
            firstnum = double.Parse(Console.ReadLine());


            Console.WriteLine("Select an operator:(+,-,*,/,%)\n");
           ops= Console.ReadLine();

            Console.WriteLine("Enter Second number\n");
            secnum = double.Parse(Console.ReadLine());

            if(ops=="+")
            {
                Answer = firstnum + secnum;
                Console.Write(Answer);

            }
            if (ops == "-")
            {
                Answer = firstnum - secnum;
                Console.Write(Answer);

            }
            if (ops == "*")
            {
                Answer = firstnum * secnum;
                Console.Write(Answer);
            }
            if (ops == "/")
            {
                Answer = firstnum / secnum;
                Console.Write(Answer);
            }
            if (ops == "%")
            {
                Answer = firstnum % secnum;
                Console.Write(Answer);

            }

            Console.ReadKey();
           
           


        }
    }
}
