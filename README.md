using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using static System.Console;

namespace ConsoleApp3
{
    internal class Program
    {
        static void Main(string[] args)
        {
            string mês = "";
            WriteLine("digite um mês:");
            mês = ReadLine();
            switch (mês)
            {
                case "Janeiro":
                case "Marco":
                case "Maio":
                case "Julho":
                case "Agosto":
                case "Outubro":
                case "Dezembro":
                    WriteLine("O mês de {0} tem 31 dias.", mês);
                    break;
                case "Fevereiro":
                    WriteLine("O mês de {0} tem 28 ou 29 dias.", mês);
                    break;
                default:
                    WriteLine("O mês de {0) tem 30 dias.", mês);
                    break;
            }
            ReadKey();
        }
    }
}
# 21-08
