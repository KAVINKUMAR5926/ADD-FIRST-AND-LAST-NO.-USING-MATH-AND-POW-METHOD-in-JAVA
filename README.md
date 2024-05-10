# ADD-FIRST-AND-LAST-NO.-USING-MATH-AND-POW-METHOD-in-JAVA
import java.util.Scanner;
public class Main
{
    public static void main(String arg[]){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int last = n%10;
        int count = (int)Math.log10(n)+1;
        int pow = (int)Math.pow(10, count-1);
        int first = n/pow;
        System.out.print(first+last);
    }
}
