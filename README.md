# Lesson1












using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace lesson1_console
{
    internal class Program
    {
        static void Main(string[] args)
        {
            string a = "problem ";
            string b = "belirlemek ";
            string c = "için ";
            string d = "şu ";
            string e = "sorular ";
            string f = "sorulabilir";
           //there is words that is gonna be in a letter for easier typing


            string g = (a + b + c + d + e + f);
            //at this code all letters(words) in a 1 letter
            Console.WriteLine(g);
            //and write to the console
            Console.ReadKey();
            //for key reader from the keyboard so that the code does not run out
        }
    }
}

