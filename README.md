# AdadFisaghoresi.sln

- **Link:** [Quera Problem #280](https://quera.org/problemset/280)
- **Description:** Write programs that accept three positive integers as input from the user and print YES if it is possible to construct a right triangle with the given side lengths and NO otherwise.
- **Solution:** Implemented in C#.

namespace adadFisaghoresi
{
    internal class Program
    {
        static void Main(string[] args)
        {
            //Console.WriteLine("Enter 3 numbers:");
            int a = Convert.ToInt32(Console.ReadLine());
            int b = Convert.ToInt32(Console.ReadLine());
            int c = Convert.ToInt32(Console.ReadLine());
            if ((a * a) + (b * b) == (c * c) || (a * a) + (c * c) == (b * b) || (b * b) + (c * c) == (a * a))
            {
                Console.WriteLine("YES");
            }
            else
            {
                Console.WriteLine("NO");
            }
        }
    }
}
