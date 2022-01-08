# PreFinal-Exam
DataType Codes

using System;

namespace DataTypesApp
{

    class Program
    {
    
    
        double pieces = 0;
        double price = 0;
        
        
        Console.Write("Enter the pieces of apple:");
        pieces = Convert.ToInt32(Console.ReadLine());
        
        Console.Write("Enter total price of " + pieces + " Apple(s):");
        price = Convert.ToDouble(Console.ReadLine());
        Console.WriteLine("The Total Price is " + price);
        Console.WriteLine("The value of original price is " + price);
        Console.WriteLine("The value of converted price is " + (int)price);
        Console.WriteLine("Press any key to exit......");
        Console.ReadKey();
        
      }
   }
}
