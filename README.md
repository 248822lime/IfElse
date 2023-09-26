# IfElse
package javaapplication35;
import java.util.Scanner;
public class JavaApplication35 {

    public static void main(String[] args) {
        Scanner input = new Scanner (System.in);
        String username,password;
        
        System.out.println("SILAHKAN MASUKAN DATA ANDA");
        System.out.print("Username \t: ");
        username = input.nextLine();
        System.out.print("Password \t: ");
        password = input.nextLine();
        
        if (username.equals("lime") && password.equals("88peng")){
            System.out.println("Login Berhasil ");    
        }else{
            System.out.println("Login Gagal ");
        }
    }  
}
