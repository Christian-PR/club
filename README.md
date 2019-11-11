/**
 * Write a description of class PositivoNegativo here.
 * 
 * @author (your name) 
 * @version (a version number or a date)
 */
import java.util.Scanner;
public class PositivoNegativo
{
   public static void main (String [] args){
    Scanner num= new Scanner(System.in);
    double a;
    System.out.println("Intrduzca un numero");
    a= num.nextDouble();
    if (a == 0)
    System.out.println("El numero es 0");
    else if(a>0)
    System.out.println("El numero es positivo");
    else
    System.out.println("El numero es negativo");
}

    }
