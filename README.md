//# NameWithHelloWorld
//Take input from user and print the user name along with a statement.


using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace NameWithHelloWorld
{
    class NameWithHelloWorld
    {
        public string NameWithHelloWorlds()
        {
            Console.WriteLine("Please enter your name : ");
            string strres = Console.ReadLine();
            Console.WriteLine("Welcome to the world of GITHUB for first time " + strres);
            return "";
        }
        static void Main(string[] args)
        {
            NameWithHelloWorld hw = new NameWithHelloWorld();
            hw.NameWithHelloWorlds();
            Console.ReadLine();
        }
    }
}
