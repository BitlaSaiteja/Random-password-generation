import java.util.*;

public class Main{
    public static void main(String[] args) {
        Scanner s=new Scanner(System.in);
        Random obj=new Random();
        System.out.println("Enter your password length: ");

        int lenght=s.nextInt();
        char[] password=new char[lenght];
        String cap="ABCDEFGHIJKLMNOPQRSTUVWXYZ";
        String small="abcdefghijklmnopqrstuvwxtz";
        String num="1234567890";
        String cases="!@#$%^&";
        String values=cap+small+num+cases;
        for(int i=0;i<lenght;i++){
       password[i]=values.charAt(obj.nextInt(values.length()));
        }
        System.out.println(password);
    }
}
