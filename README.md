# Exercicio-01---Praticas-de-Programa-o
Nome: Guilherme Junio Silva Simões .  Turma: Praticas de programação Primeiro Periodo ADS. RA: 31828661. 
using System;


namespace ExercicioProgramaçãoAds {
    class Program {
        static void Main(string[] args) {

            // Exercicio Numero 1:

            Console.ForegroundColor = ConsoleColor.DarkRed;
            Console.WriteLine("Exercicio 01!");
            Console.ResetColor();
            Console.WriteLine();

            int j = 1;

            while (j <= 40) {
                Console.Write(" "+j);
                j++;
            }
            Console.WriteLine();
            Console.ReadKey();
            Console.WriteLine();

            //Exercicio Numero 2:

            Console.ForegroundColor = ConsoleColor.DarkRed;
            Console.WriteLine("Exercicio 02!");
            Console.ResetColor();
            Console.WriteLine();

            int x = 10;
            int y = 15;

            Console.WriteLine("x = " + x);
            Console.WriteLine("O valor de x + x é " +(x + x));
            Console.WriteLine("x = ");
            Console.WriteLine((x + y) + " = " +(y + x));
            Console.ReadLine();
            Console.WriteLine();

            //Exercicio Numero 3:
            Console.ForegroundColor = ConsoleColor.DarkRed;
            Console.WriteLine("Exercicio 03!");
            Console.ResetColor();
            Console.WriteLine();
            Console.WriteLine("*\n * *\n * **\n * ***\n * ****");
            Console.ReadKey();
            Console.WriteLine();

            //Exercicio Numero 4: 
            Console.ForegroundColor = ConsoleColor.DarkRed;
            Console.WriteLine("Exercicio 04!");
            Console.ResetColor();
            Console.WriteLine();
            Console.Write("*");
            Console.Write("***");
            Console.WriteLine("*****");
            Console.Write("****");
            Console.WriteLine("**");
            Console.ReadKey();
            Console.WriteLine();

            //exercicio Numero 5:

            Console.ForegroundColor = ConsoleColor.DarkRed;
            Console.WriteLine("Exercicio 05.1!");
            Console.ResetColor();
            Console.WriteLine();
            Console.ForegroundColor = ConsoleColor.DarkGreen;
            Console.Write("Nome: Guilherme ");
            Console.ResetColor();
            Console.Write(" Sobrenome: Simões ");
            Console.ForegroundColor = ConsoleColor.DarkGreen;
            Console.Write(" Numero de Matricula: 3182228");
            Console.WriteLine();
            Console.ResetColor();

            Console.ReadKey();
            Console.WriteLine();

            //exercicio Numero 5: Segundo Exemplo

            Console.ForegroundColor = ConsoleColor.DarkRed;
            Console.WriteLine("Exercicio 05.2!");
            Console.ResetColor();
            Console.WriteLine();
            string nome;
            string SobreNome;
            int idade;

            Console.Write("Digite seu nome: ");
            nome = Console.ReadLine();

            Console.Write("Digite seu Sobrenome: ");
            SobreNome = Console.ReadLine();

            Console.Write("Digite sua idade: ");
            idade = Convert.ToInt16(Console.ReadLine());

            Console.ForegroundColor = ConsoleColor.DarkGreen;
            Console.WriteLine(nome);
            Console.ResetColor();
                       
            Console.WriteLine(SobreNome);
            
            Console.ForegroundColor = ConsoleColor.DarkBlue;
            Console.WriteLine(idade);
            Console.ResetColor();



            Console.ReadKey();

            Console.WriteLine();


            //Exercicio 06:
            Console.ForegroundColor = ConsoleColor.DarkRed;
            Console.WriteLine("Exercicio 06!");
            Console.ResetColor();
            Console.WriteLine();
            double x1;
            double y2;
            

            Console.Write("Digite um numero: ");
            x1 = double.Parse(Console.ReadLine());
            Console.Write("Digite um numero: ");
            y2 = double.Parse(Console.ReadLine());

            Console.WriteLine("Resultado da soma: "+ (x1 + y2) + " Resultado da Subtração: "+ (x1 - y2)+ " Resultado da Multiplicação: " + ","+ (x1 * y2)+ " Resultado da Divisão: "+ (x1 / y2));
            Console.ReadLine();

            Console.WriteLine();       
            


            //Exercicio 07:
            Console.ForegroundColor = ConsoleColor.DarkRed;
            Console.WriteLine("Exercicio 07!");
            Console.ResetColor();

            double raio;
            double diametro;
            double circunferencia;
            double resultado1;


            Console.Write("Digite a área o raio de um circulo: ");
            raio = double.Parse(Console.ReadLine());
            Console.Write("O Diametro do Cirulo é: {0}", raio * raio);
            Console.Write(" A Circunferencia do Cirulo é: {0}", Math.PI * raio);
            Console.Write(" Área do Cirulo é: {0}", Math.PI * Math.Pow(2,raio));
            Console.WriteLine();
            Console.ReadKey();
            Console.WriteLine();

            //Exercicio 08:
            Console.ForegroundColor = ConsoleColor.DarkRed;
            Console.WriteLine("Exercicio 08!");
            Console.ResetColor();

            int a, b;
            double resultado;
            Console.WriteLine("Digite um numero inteiro: ");
            a = int.Parse(Console.ReadLine());
            Console.WriteLine("Digite um numero inteiro: ");
            b = int.Parse(Console.ReadLine());
            Console.ReadLine();

            resultado = a % b;
            if ((a % b) == 0) {
                Console.WriteLine("Será Multiplo");
             }
            else
            {
                Console.Write("O resto da divisão é: {0}", resultado);
            }
            Console.ReadLine();
            Console.WriteLine();


            //Exercicio 09:




            Console.WriteLine();
            //Exercicio 10



            Console.WriteLine("\tnumero \tquadrado \tcubo");
            for (int i = 0; i <= 10; i++) {
                Console.WriteLine("%d\t %d\t \t%d\n", i, i * i, i * i * i);
            }

             
             
        }

        
                                                   
    }
}
