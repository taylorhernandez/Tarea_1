using System;
 
public class conversion
{
    public static void Main()
    {

		
		float valor2 = (float) 10.1;
		float valor3 = (float) 2.87;
		float valor1;
        float operar;
		float operar2;
		
		Console.WriteLine("Introduzca la cantidad de celsius");
        valor1 = Convert.ToSingle(Console.ReadLine());
        operar = valor1*valor2;
		operar2 = valor1*valor3;

        Console.WriteLine("El resultado esperado:" ) ; 
       
		Console.WriteLine("Kelvin = {2}", 
		valor1, valor2, operar);

		Console.WriteLine("Fahrenheit = {2}", 
		valor1, valor3, operar2);

	}
}

