
# JarProjects - New_br_at_910_commit before delete

import java.util.Scanner;
 
class AddNumbers
{
   public int substarction(int a, int b){
   return a-b;
   }
   //Main Add Method
   public static void main(String args[])
   {
      int x, y, z;
      System.out.println("Enter two integers to calculate their sum ");
      Scanner in = new Scanner(System.in);
      x = in.nextInt();
      y = in.nextInt();
      z = x + y;
      System.out.println("Sum of entered integers = "+z);
   }
   public int mul(int a, int b){
	return a*b;
   }
}
//AddNumbers Class
