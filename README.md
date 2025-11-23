# cwiczenia2
czesc 1
using System;

public class HelloWorld
{
    public static void Main(string[] args)
   
    {
        int[] liczbaklientow = { 100, 150, 40, 20, 200, 58, 90, 43, 120, 49, 709, 450 };
        int suma =0;
       for (int i = 0; i < 12; i++)
       suma = suma + liczbaklientow[i];
        Console.WriteLine( suma );
        
}
}
czesc 2
using System;

public class HelloWorld
{
    public static void Main(string[] args)
   
    {
        int[] liczbaklientow = { 100, 150, 40, 20, 200, 58, 90, 43, 120, 49, 430, 450 };
        int suma =0;
        int maks =0;
       for (int i = 0; i < 12; i++)
      { suma = suma + liczbaklientow[i];
        if (liczbaklientow[i] > maks);
        { maks = liczbaklientow[i];
        }
      }
        Console.WriteLine(maks);
}
}
