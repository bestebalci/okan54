package okan5;
import java.util.Scanner;
public class okan54 {
	
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		//veri yarat
		double gelir;
		int status;
		
		
		
		Scanner input = new Scanner (System.in);
		
		//status sor
		System.out.println("Lütfen status u gir");
		status = input.nextInt();
		
		//gelir sor
		System.out.println("Lütfen gelirinizi girin");
		gelir = input.nextDouble();
		
		//status e ve gelere baglı olarak vergi oranını goster
		
		if (status == 1) {
			if (gelir < 8350){
				System.out.println("orani %10");
			} else if (gelir <= 33950){
				System.out.println("oranı %15");
			
				
			} else if (gelir < 82250){
				System.out.println("oranı %25");
			} else if (gelir <= 171550){
				System.out.println("oranı %28");
			} else if (gelir <= 372950){
				System.out.println("oranı %33");
				
		
		
			
		} else if (status == 2) {
			
		} else if (status == 3){
			
		} else if (status == 4){
		}
		
		}
	}
}
