using System;
 
public class Ejercicio5
{
    public static void Main()

        {
            int A,B,tem;
       Console.WriteLine("Ingresa el valor de A ");
         A=Convert.ToInt32(Console.ReadLine()); 
       Console.WriteLine("Ingresa el valor de B ");
         B=Convert.ToInt32(Console.ReadLine()); 
         tem=A;
         A=B;
         B=tem;
    Console.WriteLine("Ahora el valor de A es: " + A + " y el valor de B es: " + B);
         Console.ReadLine();
        }
    }
