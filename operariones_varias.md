using System;
 
public class Ejercicio4
{
    public static void Main()
    {
        int valor1 = -1, valor2 = 3, valor3 = 5 ;
        float operacion1;
 
        Console.WriteLine("Vamos a operar -1 + 3 *5");
        operacion1 = valor1+(valor2*valor3);
        Console.WriteLine("El resultado es {0}", operacion1);
		Console.WriteLine();			
		
		int valor4 = 24, valor5 = 5;
		float valor6 = (float) 0.07;
        float operacion2;
 
        Console.WriteLine("Vamos a operar (24 + 5) 7%");
        operacion2 = (valor4+valor5)*valor6;
        Console.WriteLine("El resultado es {0}", operacion2);
		Console.WriteLine();
		
		
		int valor7 = 15, valor8 = -4, valor9 = 6, valor10 = 11 ;
		float operacion3;
 
        Console.WriteLine("15 + -4 * 6/11");
        operacion3 = (valor7+valor8)*(valor9/valor10);
        Console.WriteLine("El resultado es {0}", operacion3);
		Console.WriteLine();
		
		int valor11 = 2, valor12 = 10, valor13 = 6, valor14 = 1, valor16 = 2;
		float valor15 = (float) -0.7;
		float operacion6;
 
        Console.WriteLine("2 + 10/6 * 1 - 7% 2");
        operacion6 = (valor11+valor12/valor13)*(valor14-valor15*valor16);
        Console.WriteLine("El

