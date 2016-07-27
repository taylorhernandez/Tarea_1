
using System;
 
public class Ejercicio8
{
    public static void Main()
    {

        
            int res;//variable para guardar el resultado de la multiplicación
            for (int i = 1; i <= 10; i++)//ciclo for para indicar cada tabla
            {
                Console.WriteLine("     Tabla del " + i);//se indica la tabla en que está
                for (int j = 1; j <= 10; j++)//ciclo for para calcular una tabla
                {
                    res = j * i;//resultado es igual a j multiplicado por i
                    Console.WriteLine(+j + " x " + i + " = " + res);//se escribe la operación en pantalla ejemplo  1 x 5 = 5
                }
            }
            Console.ReadLine();//se detiene pantalla
        }
}
