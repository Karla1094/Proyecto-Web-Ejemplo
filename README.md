# Proyecto-Web-Ejemplo
Proyecto para la certificación de Git
public class README.md{
 public static void main(String[] args) {
        
        // Declaración de arreglo para guardar los números del bingo (del 1 al 75)
        int [][] bingo = new int[15][5];
        int contador = 1;

        // Llenar el arreglo con números del 1 al 75
        for(int columna = 0; columna < 5; columna++) {
            for(int fila = 0; fila < 15; fila++) {
                bingo[fila][columna] = contador;
                contador++;
            }
        }

        // Impresión de los números del 1 al 75
        System.out.println("****************** Impresión de los números del 1 al 75 **************************");
        System.out.println("\tB\tI\tN\tG\tO");
        
 }
 }