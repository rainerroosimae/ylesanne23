# ylesanne23

import java.util.Scanner;
public class ylesanne23 {

	public static void main(String[] args) {
		 System.out.println ("Teretulemast täringut mängima!");
	        
		   //Täringu veeretamine.
		    	
		    		int taring1, taring2;//muutujad
		    		int rollcount; //kokkulugeja
		    		rollcount = 0; //algväärtus
					
				do {
					taring1 = (int)(Math.random()*6) + 1; //randomiga täringuväärtus
		            taring2 = (int)(Math.random()*6) + 1; //randomiga täringuväärtus
		            rollcount++; //lisandumine
				}	while ( taring1 != taring2 );{ //väärtuste võrdlemine
							System.out.println("Kas soovite veel täringut mängida? 1 = Jah, 2 = Ei");
							Scanner keyboard = new Scanner(System.in); //sisendi saamine
							int userinput=keyboard.nextInt();
				}
												
				System.out.println("Võitsite " + rollcount + " veeretamisega.");
				
			}
		}
	
