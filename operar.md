using System;
 
public class operar
{
    public static void Main()
    {
        float primerNumero;
        float segundoNumero;
		float terceroNumero;
		float operar;
		float operar1;
		
 
        Console.WriteLine("Introduce el primer número");
        primerNumero = Convert.ToSingle(Console.ReadLine());
        Console.WriteLine("Introduce el segundo número");
        segundoNumero = Convert.ToSingle(Console.ReadLine());
		Console.WriteLine("Introduce el tercer número");
		
        terceroNumero = Convert.ToSingle(Console.ReadLine());
		operar = (primerNumero + terceroNumero)*segundoNumero;
		operar1 = (primerNumero + primerNumero)*segundoNumero*terceroNumero;
		
 
        Console.WriteLine("Resultado de números especificados  de {0}  {1}  {2} (x+y)*z  es:   {3} ", 
          primerNumero, segundoNumero, terceroNumero,  operar);

		
		Console.WriteLine("Resultado de números especificados  de {0}  {1}  {2} (x+x)*y*z  es:   {3} ", 
	    primerNumero, segundoNumero, terceroNumero,  operar1);
		

		}
}
