# Greatest-of-three-numbers
java program to check Greatest of three numbers
import java.util.Scanner;
public class BiggestNumber
{
   public static void main(String[]args)
   {
      int a,y,z;
      Scanner s=new Scanner(System.in);
      System.out.print("Enter the First number:");
      a=s.nextInt();
      System.out.println("Enter the Second number:");
      y=s.nextInt();
      System.out.println("Enter the Third number:");
      z=s.nextInt();
      if(a>y&&x>z)
      {
         System.out.println("Largest number is:"+a);
      }
      else if(y>x&&y>z)
      {
         System.out.println("Largest number is:"+y);
      }
      else{
      System.out.println("Largest number is:"+z);
      }
   }
 }
