# Eclids-game
package javaapplication1;
import java.util.Scanner;

public class JavaApplication1 { 
    public static void main(String[] args) {
         Scanner input=new Scanner(System.in);
    int a,b,sum,gcd;
    System.out.println("a=");
    a=input.nextInt();
    System.out.println("b");
    b=input.nextInt();
    System.out.println("gcd");
    gcd=input.nextInt();
   System.out.println("sum");
   
   if(a>b&&a%2==0){
       sum=a/gcd;
        System.out.println("sum= ");
        System.out.println(sum);
       System.out.println("Secound player is win in first");
       System.out.println("First player is lost");
       
   }
   else if(a>b&&a%2!=0){
       sum=a/gcd;
        System.out.println("sum=");
        System.out.println(sum);
       System.out.println("First player is win first");
       System.out.println("Secound player is lost");
       
   }
   else if(b>a){
     int x=b;
     b=a;
     x=a;
     sum=a/gcd;
     System.out.println("sum=");
        System.out.println(sum);
         System.out.println("First player is win first");
          System.out.println("Secound player is lost ");
        
    }
}
}
