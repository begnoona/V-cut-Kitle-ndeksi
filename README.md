import java.util.Scanner;

public class Main2 {



    public static void main(String[] args) {

    
        //Java ile kullanıcıdan boy ve kilo değerlerini alıp bir değişkene atayın.
        // Aşağıdaki formüle göre kullanıcının "Vücut Kitle İndeks" değerini hesaplayıp ekrana yazdırın.
        double kilo,boy,formul;
        
        Scanner input = new Scanner(System.in);
        
        System.out.print("Kilo: ");
        kilo = input.nextDouble();
        System.out.print("Boy: ");
        boy = input.nextDouble();
        formul=kilo/(boy * boy);
        
        System.out.println("vücut kitle indeksi: "+formul);


    }
}
