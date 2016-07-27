using System;
 
public class promedio
{
    public static void Main()
    {
        float primerNumero;
        float segundoNumero;
		float terceroNumero;
		float cuartoNumero;
        float promedio;
 
        Console.WriteLine("Introduce el primer número");
        primerNumero = Convert.ToSingle(Console.ReadLine());
        Console.WriteLine("Introduce el segundo número");
        segundoNumero = Convert.ToSingle(Console.ReadLine());
		Console.WriteLine("Introduce el tercer número");
        terceroNumero = Convert.ToSingle(Console.ReadLine());
		Console.WriteLine("Introduce el cuarto número");
        cuartoNumero = Convert.ToSingle(Console.ReadLine());
        promedio = (primerNumero + segundoNumero + terceroNumero + cuartoNumero)/4;
 
        Console.WriteLine("El promedio de {0}  {1}  {2} {3} es:   {4}", 
          primerNumero, segundoNumero, terceroNumero, cuartoNumero, promedio);
		}
}


