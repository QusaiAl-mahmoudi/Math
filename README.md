
package Qusai;
import java.util.Scanner;
public class  Math{
    public static void main (String [] args){
        Scanner input=new Scanner(System.in);
       float Number1,Number2;
        System.out.println("Enter the first number:");
        Number1=input.nextInt();
        System.out.println("Enter ths secand Number:");
        Number2=input.nextInt();
        System.out.println("Enter the calculation :");
       String Math=input.next();
        float s,b,e,w;
        switch (Math)
        { case "+":
           s= Number1 + Number2;
            System.out.println(s);
            break;
            case "-":
            b= Number1- Number2;
            System.out.println(b);
            break;
            case "*":
            e= Number1*Number2;
            System.out.println(e);
            break;
            case" / ":
            w= Number1/Number2;
            System.out.println(w);
            break;
            default :
            System.out.println("Sorry I can net anderstsnd you  try again");
        }
    }
}

