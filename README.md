# proyectoalgoritmopackage concesionaria;
import java.util.Scanner;
public class Concesionaria {

    public static void main(String[] args) {
        // TODO code application logic here
        boolean salir = false;
        boolean vehiculo=false;
        int opcion;
        int auto;
        int tipo;
        String Sedan;

        Scanner sc = new Scanner(System.in);
        /*Bucle que permite repetir el menu*/
        while (!salir) {
            System.out.println("----------------");
            System.out.print("Consecionario de Autos \n-Menu Principal-\n 1. selecionar Automovil \n 2. Salir \n");
            System.out.print("Ingrese la opcion que desea ejecutar: ");
            opcion = sc.nextInt();
            /*Switch con cada uno de los casos para las diferentes opciones del menu*/
            switch (opcion) {
                case 1:
                    System.out.println("-----------");
                    System.out.print("Consecionario de Autos \n- Seleccion de Gama de vehiculo - \n");
                    System.out.print("1.- Sedan economico\n 2.-Sedan\n 3.Deportivo\n4. Hibrido\n5. Coupe\n6. Coupe Deportivo\n7. Compacto\n8. Hatchback\n9. economico version rally\n 10. Regresar al Menu Principal\n");
                    System.out.print("Ingrese Gama de Vehiculo: ");
                    auto=sc.nextInt();
                    break;
                case 2:
                    System.out.println("Hasta luego!");
                    salir = true;//Se pone la variable salir en verdadero para salir del Bucle
                    break;
                default:
                    System.out.print("Opcion no valida!");
        }
        }
       
}
    }
