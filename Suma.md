using System;
 
public class Ejercicio_2
{
    public static void Main()
    {
        float primerNumero;
        float segundoNumero;
        float suma;
 
        Console.WriteLine("Introduce el primer número");
        primerNumero = Convert.ToSingle(Console.ReadLine());
        Console.WriteLine("Introduce el segundo número");
        segundoNumero = Convert.ToSingle(Console.ReadLine());
        Division = primerNumero + segundoNumero;
 
        Console.WriteLine("La suma es {0} y {1} es {2}", 
          primerNumero, segundoNumero, suma);
    }
}
