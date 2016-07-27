using System;
 
public class crear_columna
{
    public static void Main()
    {
        float primerNumero;
		float columna;

		
 
        Console.WriteLine("Escribe un numero");
        primerNumero = Convert.ToSingle(Console.ReadLine());
        columna = primerNumero;
		
 
        Console.WriteLine("El resultado esperado:" ) ; 
       
		Console.WriteLine("{0}{0}{0} ", 
		columna, columna);
		
		Console.WriteLine("{0} {0} ", 
		columna, columna);
			
       
		Console.WriteLine("{0} {0} ", 
		columna, columna);
		
		Console.WriteLine("{0} {0} ", 
		columna, columna);
		
		Console.WriteLine("{0}{0}{0} ", 
		columna, columna);

		}
}

