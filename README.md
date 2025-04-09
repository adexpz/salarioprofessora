using System;
string nome = "salariohora, Horaaula, salario, desconto, total, inss";
					
Console.WriteLine("digite quantos ganha por hora");
double horaaula = double.Parse(Console.ReadLine());

Console.WriteLine("digite quantos dias trabalhados");
double salariohora = double.Parse(Console.ReadLine());

double resultado = horaaula * salariohora;
Console.WriteLine("o salario bruto e:" + resultado);

Console.WriteLine("digite o total descontado");
double desconto = double.Parse(Console.ReadLine());

double valordescontado = resultado * (desconto /100);
double total = resultado - valordescontado;
double inss = resultado * 0.2;

Console.WriteLine("o salario com inss descontado é:" + total);
Console.WriteLine("o total decontado foi:" + inss);
