using System;

namespace HolaMundo
{
    class Program
    {
        static void Main(string[] args)
        {
            // Muestra un mensaje de bienvenida en la consola
            Console.WriteLine("¡Hola, Mundo!");

            // Pide al usuario que ingrese su nombre
            Console.Write("Por favor, ingresa tu nombre: ");
            string nombre = Console.ReadLine();

            // Saluda al usuario usando su nombre
            Console.WriteLine($"¡Hola, {nombre}!");

            // Pide al usuario que ingrese dos números para sumarlos
            Console.Write("Ingresa el primer número: ");
            int numero1 = Convert.ToInt32(Console.ReadLine());

            Console.Write("Ingresa el segundo número: ");
            int numero2 = Convert.ToInt32(Console.ReadLine());

            int suma = numero1 + numero2;
            Console.WriteLine($"La suma de {numero1} y {numero2} es: {suma}");

            // Mantén la consola abierta hasta que el usuario presione una tecla
            Console.WriteLine("Presiona cualquier tecla para salir...");
            Console.ReadKey();
        }
    }
}

