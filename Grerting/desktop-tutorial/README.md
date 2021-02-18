using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Grerting
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.Write("\nКак вас зовут?");
            var name = Console.ReadLine();
            var date = DateTime.Now;
            Console.WriteLine($"\nПривет, {name}, на {date:d} в {date:t}!");
            
            Console.ReadKey(true);

        }

    }
}
