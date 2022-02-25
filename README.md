import java.util.Scanner;

class Calculator  
{
    public static void main(String args[])
    {
     Scanner sc=new Scanner(System.in);
      int a=sc.nextInt();
      int b=sc.nextInt();
      int c;
      int d;
      int e;
      int f;
      System.out.println("Enter a and b:");
      String name=sc.nextLine();
      c=a+b;
      d=a-b;
      e=a*b;
      f=a/b;
    System.out.println("c="+c);
    System.out.println("d="+d);
    System.out.println("e="+e);
    System.out.println("f="+f);
    }

 }   
