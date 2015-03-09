# Tabla-de-multiplicar
package tablamultiplicarnumero;
import java.util.*;

public class TablaMultiplicarNumero {

    
    public static void main(String[] args) {
       Scanner lec=new Scanner(System.in);
        int N,C=1;
       
       System.out.print("Introduce un número: ");
         N=lec.nextInt(); 
        
       System.out.println("Tabla de multiplicar del " +N);
       while(C<=10){
           System.out.println(N+"*"+C+"="+N*C);
           C++;
       }
    }
    
}
