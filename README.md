



import java.util.Scanner;
// utiliza el Scanner para que el programa pueda recibir datos escritos por el usuario//

public class Main {
    public static void main (String[] args){
        Scanner s =  new Scanner(System.in);
        System.out.println("Ingresa un numero entero: ");

        int a = s.nextInt();
        // Comprueba el primer numero entero que ingresa el usuario en la variable a//

        if (a >= 18 ) {
            // Se comprueba si el numero es mayor o menor//

            if ( a  >=80){
                // Comprueba si el segundo numero  es mayor o igual a 80//


                System.out.println("Resultado: STATUS_A");
            } else {
                // Se utiliza cuando la condicion anterior o se cumple//
                System.out.println("Resultado: STATUS_B");
            }
        } else {
            System.out.println("Resultado: STATUS_C");
        }
        s.close();
    }
}

//Este programa solicita dos numeros enteros al usuario y mediante condiciones 
// como if y else determina que resultado mostrar dependiendo  que valores se ingresen//