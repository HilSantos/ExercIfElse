# Calcule a media das três notas usando IfElse

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ExercIfElse
{
    public class Program
    {
        static void Main(string[] args)
        {
decimal nota1, nota2, nota3, media;

  Console.WriteLine("Informe a nota1: ");
            nota1 = Convert.ToDecimal(Console.ReadLine());

  Console.WriteLine("Informe a nota2: ");
            nota2 = Convert.ToDecimal(Console.ReadLine());

  Console.WriteLine("informe a nota3: ");
            nota3 = Convert.ToDecimal(Console.ReadLine());

  media = (nota1 + nota2 + nota3) / 3;

  if (media >= 7)
            {
                Console.WriteLine("Aprovado!");
                Console.WriteLine("Media: " + media);
            }
            else
            {
                Console.WriteLine("Reprovado!");
                Console.WriteLine("Media: " + media);
            }
            Console.WriteLine("Calcule a media: " + media);
            media = Convert.ToDecimal(Console.ReadLine());


  Console.ReadKey();
        }
    }
}
