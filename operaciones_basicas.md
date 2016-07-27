using System;
 
public class multiplicacion 
{
    public static void Main()
    {
        float primerNumero;
        float segundoNumero;
		float suma;
		float resta;
		float multiplica;
 		float division;
		
        Console.WriteLine("Introduce el primer número");
        primerNumero = Convert.ToSingle(Console.ReadLine());
        Console.WriteLine("Introduce el segundo número");
        segundoNumero = Convert.ToSingle(Console.ReadLine());
		multiplica = primerNumero * segundoNumero;
		suma = primerNumero + segundoNumero;
		resta = primerNumero - segundoNumero;
        division = primerNumero / segundoNumero;
        
		
		Console.WriteLine(" El resultado esperado es: ");
        Console.WriteLine(" {0} X {1}  = {2}", 
		primerNumero, segundoNumero, multiplica);
		Console.WriteLine(" {0} + {1}  = {2}",
		primerNumero, segundoNumero, suma);
		Console.WriteLine(" {0} - {1}  = {2}",
		primerNumero, segundoNumero, resta);
		Console.WriteLine(" {0} / {1}  = {2}",
		primerNumero, segundoNumero, division);
    }
}


