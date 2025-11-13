# desarrollo-de-aplicaciones-de-ultima-generacion

#ejercicio1
using System;

class epa
{
    static void Main()
    {
        Console.Write("Ingresa tu nombre: ");
        string nombre = Console.ReadLine();
        Console.WriteLine("Hola, " + nombre + "!");
    }
}

#ejercicio2
using System;

class epa
{
    static void Main()
    {
        Console.Write("Ingresa tu nombre: ");
        string nombre = Console.ReadLine();
        Console.ForegroundColor = ConsoleColor.Red;
        Console.WriteLine("Hola, " + nombre + " ❤️");
        Console.ResetColor();
    }
}

#ejercicio3
using System;

class epa
{
    static void Main()
    {
        string nombre = "Nicol";
        int edad = 19;
        Console.WriteLine("Mi nombre es " + nombre + " y tengo " + edad );
    }
}

#ejercicio4
using System;

class epa
{
    static void Main()
    {
        string nombre = "Nicol";
        int edad = 19;

        string mensaje = string.Format("Mi nombre es {0} y tengo {1}", nombre, edad);
        Console.WriteLine(mensaje);
    }
}
