# factorial

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package factorial;

import java.util.Scanner;

/**
 *
 * @author Adolf
 */
public class Factorial {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner leer=new Scanner(System.in);
        System.out.println("Ingresar Numero: ");
        int numero=leer.nextInt();
        int factorial=1;
        
        while(numero!=0)
        {
            factorial *=numero;
            numero--;
        }        
        System.out.println("Su Factorial es: "+factorial);
    }
    
    
}
