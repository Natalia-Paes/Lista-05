# Lista-05
Códigos referente à lista 05
import java.util.Scanner;

public class Ex01 {
    public static void main(String[] args) throws Exception {

        System.out.println("Informe um número: ");
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        executeNx(n);
        sc.close();
    }

    public static void executeNx(int n) {
        for (int a = 1; a <= n; a++) {
            for (int b = 1; b <= a; b++) {
                System.out.println(a + "");
            }
            System.out.println("");
        }
    }
}
