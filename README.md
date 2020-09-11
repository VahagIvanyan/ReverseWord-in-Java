# ReverseWord-in-Java
import java.util.Scanner;
public class Main {
    public static void Reverse(String toReverse){
        int length = toReverse.length();
            while( length > 0) {
                System.out.println(toReverse.charAt(length-1));
                length--;
            }
    }
    public static void main(String[] args) {
        System.out.println("Enter a Word: \n");
        Scanner in = new Scanner(System.in);
        String Word = in.nextLine();
        Reverse(Word);
    }
}
