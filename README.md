#SOMA
import java.util.Scanner;

public class resto {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("digite um numero:");
        int n1 = sc.nextInt();
        System.out.print("digite outro numero:");
        int n2 = sc.nextInt();
        int resultado = n1 % n2;
        System.out.println("o resto da divisão é:" + resultado);
    }
}



#NOME
import java.util.Scanner;

public class nome {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("qual seu nome?");
        String nome = sc.nextLine();

        System.out.print(nome);
    }
}



#OPERAÇAO
import java.util.Scanner;

public class operaçao {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("digite um numero:");
        int n1 = sc.nextInt();

        System.out.print("digite um outro numero:");
        int n2 = sc.nextInt();

        int resultado = n1 + n2;
        int resultado1 = n1 - n2;
        int resultado3 = n1 * n2;
        int resultado4 = n1 / n2;

        System.out.println("a soma dos numeros é:" + resultado);
        System.out.println("a subtração dos numeros é:" + resultado1);
        System.out.println("a multiplicação dos numeros é:" + resultado3);
        System.out.println("a divisão dos numeros é:" + resultado4);
    }
}




#RESTO
import java.util.Scanner;

public class resto {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("digite um numero:");
        int n1 = sc.nextInt();
        System.out.print("digite outro numero:");
        int n2 = sc.nextInt();
        int resultado = n1 % n2;
        System.out.println("o resto da divisão é:" + resultado);
    }
}
