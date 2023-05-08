# Not Ortalaması Hesaplayan Program
* Java ile Matematik, Fizik, Kimya, Türkçe, Tarih ve Müzik derslerinin sınav puanlarını kullanıcıdan alıp puanların ortalamasını hesaplayıp çıkan sonuç 60 veya 60'ın üzerinde ise ekrana "Sınıfı Geçti" ,60'ın altında ise ekrana "Sınıfta Kaldı" yazdıran bir program yazıyoruz.
```
import java.util.Scanner;

public class NotOrt {
    public static void main(String[] args){
        Scanner input=new Scanner(System.in);

        double mat,fizik,kimya,turkce,tarih,muzik;

        System.out.print("Matematik : ");
        mat=input.nextDouble();

        System.out.print("Fizik :");
        fizik=input.nextDouble();

        System.out.print("Kimya :");
        kimya=input.nextDouble();

        System.out.print("Türkçe :");
        turkce=input.nextDouble();

        System.out.print("Tarih :");
        tarih=input.nextDouble();

        System.out.print("Müzik :");
        muzik=input.nextDouble();

        double toplam = mat + fizik + kimya + turkce + tarih + muzik ;
        double sonuc = toplam / 6.0;

        System.out.println("Ders Notu Ortalaması :"+sonuc);
        String durum = (sonuc>=60) ? "Sınıfı Geçti" : "Sınıfta Kaldı";
        System.out.println("Durum Değerlendirmesi : "+durum);
        
    }
}
```
# Patika Profilim

***

<a href="https://app.patika.dev/krblttrkn">Patika Linkim</a>