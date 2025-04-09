using System;
decimal salariohora, Horaaula, salario, desconto, total, inss;

Console.WriteLine("digite quantos ganha por hora");
decimal horaaula = double.Parse(Console.ReadLine());

Console.WriteLine("digite quantos dias trabalhados");
decimal salariohora = double.Parse(Console.ReadLine());

decimal resultado = horaaula * salariohora;

Console.WriteLine("digite o total descontado");
decimal desconto = double.Parse(Console.ReadLine());

decimal valordescontado = resultado * (desconto / 100);
decimal total = resultado - valordescontado;
decimal inss = resultado * 0.2;

Console.WriteLine("o salario bruto e:" + resultado);
Console.WriteLine("o salario com inss descontado é:" + total);
Console.WriteLine("o total decontado foi:" + inss);
