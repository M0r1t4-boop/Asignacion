Ejercicio02

namespace _02ejercicio
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int numero;
            int suma = 0;
            do
            {
                Console.WriteLine("Ingrese un número (0 para terminar): ");
                numero=int.Parse(Console.ReadLine());
                suma += numero;
            }while(numero!=0);
            Console.WriteLine($"La suma total de los número ingresados es: {suma}");
        }
    }
}
