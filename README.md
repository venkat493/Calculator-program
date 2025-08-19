# Calculator-program
import java.util.*;
public class Calculator {
    public static void main(String[]args){
        Scanner sc=new Scanner(System.in);   
        int a=sc.nextInt(); // get two inputs from user
        int b=sc.nextInt();
        
        int c=a+b;
        System.out.print("The Addition of two numbers is:"); //Addition
        System.out.print(c);
        System.out.println();

        int g=a-b;
        System.out.print("The subraction of two numbers is:"); //subraction
        System.out.print(g);
         System.out.println();


        int j=a*b;
        System.out.print("The Multiplication of two numbers is:"); //Multiplication
        System.out.print(j);
         System.out.println();


        int l=a/b;
        System.out.print("The Division of two numbers is:"); //Division
        System.out.print(l);
         System.out.println();


    }
}
