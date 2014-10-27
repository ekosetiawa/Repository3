Repository3
===========

Tugas Repository 3
import java.util.Scanner;

public class Repository2 {
    public static void main(String[] args) {
        Scanner Masuk = new Scanner (System.in);
        String[]Nama  = new  String[5];
        String[]Nilai = new  String [5];
        
        for (int e=0;e<2;e++)
        {
            System.out.print("Masukan Nama Ke "+(e+1)+" : ");
            Nama [0] = Masuk.nextLine();
            System.out.print("Masukan Nilai Ke "+(e+1)+" : ");
            Nilai[0] = Masuk.nextLine();
        }
        System.out.println("");
        for (int i=0;i<2;i++)
        System.out.println("Nama "+Nama[0]+" Nilai :"+Nilai[0]);
    }
}
