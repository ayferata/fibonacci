# fibonacci
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner("Eleman sayısı: ");
        int n = sc.nextInt();
        int b= 0, c= 1, d;

        for (int i=1;i<=n; i++);
        d=b+c;
        System.out.println(b+"+"+c+"="+d);
        b=c;
        c=d;
        System.out.println("");

        }
    }
