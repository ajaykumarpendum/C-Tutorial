using System;  
public class GotoExample  
    {  
      public static void Main(string[] args)  
      {  
      First:  
          Console.WriteLine("You are not eligible to vote!");  
  
      Console.WriteLine("Enter your age:\n");  
      int age = Convert.ToInt32(Console.ReadLine());  
      if (age < 18){  
              goto First;  
      }  
      else  
      {  
              Console.WriteLine("You are eligible to vote!");   
      }  
      }  
   }  
   
