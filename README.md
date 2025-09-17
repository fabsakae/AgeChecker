## AgenteIA

import java.util.Scanner;

public class AgeChecker{
    public static void main(String[] args){
        Scanner t= new Scanner(System.in);
        System.out.println ("Em que ano você nasceu?");
        int nasc = t.nextInt();
    
        int i = 2025 - nasc;
        System.out.println("sua idade é :" + i);
        if (i >= 18){
            System.out.println("Maior de Idade");
        
         }else{
            System.out.println("Menor de Idade");
        }
        t.close();
    }
}
