import java.util.Scanner;
public class teste {

    public static void main(String []args)
    {
    try (Scanner teclado = new Scanner (System.in)) {
        Double F;
        double soma;


        System.out.println("Digite o valor em Fahrenheit");
         F = teclado.nextDouble();

         soma = (5*(F-32)/9);

        System.out.println("a soma da:"+soma);
    }
   
    }
 

}
