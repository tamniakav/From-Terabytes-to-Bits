# From-Terabytes-to-Bits
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace _7.From_Terabytes_to_Bits
{
    class Program
    {
        static void Main(string[] args)
        {
            double tb = double.Parse(Console.ReadLine());

            long x = 1024;
            double bits = tb * (Math.Pow(x, 4) * 8);

            Console.WriteLine(bits);
        }
    }
}
