# hesap-makinasi
Java101_7 Switch case ile hesap makinası
/* Ödev Patika.dev
Videodaki hesap makinesini switch-case kullanarak yapınız.

import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	    int n1, n2, islem ;
	    Scanner input=new Scanner(System.in);
	    System.out.print("İlk sayıyı giriniz :");
	    n1=input.nextInt();
	    System.out.print("İkinci sayıyı giriniz :");
	    n2=input.nextInt();
	    System.out.println("Yapmak istediğiniz işlemi seçiniz\n\n1-Toplama\n2-Çıkarma\n3-Çarpma\n4-Bölme");
	    System.out.print("İşlem :");
	    islem=input.nextInt();
	    
	    switch(islem) {
	    case 1 :
	        System.out.print("Toplama işleminin sonucu :"+ (n1+n2));
	        break;
	    case 2 :
	        System.out.print("Çıkarma işleminin sonucu :"+ (n1-n2));
	        break;
	    case 3 :
	        System.out.print("Çarpma işleminin sonucu :"+ (n1*n2));
	        break;
	    case 4 :
	        if (n2!=0) {
	            System.out.println("Bölme işleminin sonucu :"+ (n1/n2));
	        } else {
	            System.out.print("Bir sayı sıfıra bölünemez.");
	        } break;
	        
	    default :
	        System.out.print("Yanlış rakamı tuşladınız.\nLütfen tekrar deneyiniz");
	        break;
	    
	    
	    
	    }
	
	}
}
