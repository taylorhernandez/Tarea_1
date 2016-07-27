using System;
 
public class multiplicacion 
{
    public static void Main()
    {
        float primerNumero;
        float segundoNumero;
		float terceroNumero;
        float multiplica;
 
        Console.WriteLine("Introduce el primer número");
        primerNumero = Convert.ToSingle(Console.ReadLine());
        Console.WriteLine("Introduce el segundo número");
        segundoNumero = Convert.ToSingle(Console.ReadLine());
		Console.WriteLine("Introduce el tercer número");
        terceroNumero = Convert.ToSingle(Console.ReadLine());
        multiplica = primerNumero * segundoNumero * terceroNumero;
 
        Console.WriteLine("El resultado esperado es {0} X {1} X {2}  = {3}", 
          primerNumero, segundoNumero, terceroNumero, multiplica);
    }
}

