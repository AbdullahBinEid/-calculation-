# -calculation-
package alculation;

import java.util.Scanner;

public class alculation {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.print("enter a number:");
		Scanner input = new Scanner(System.in); 
		
		  int a = input.nextInt();
		  int b = input.nextInt();
		  	
		  
		 System.out.println("enter the calculation:");
		 Scanner number = new Scanner(System.in);
		 char calculation = number.next().charAt(0);
		 
		
		    switch (calculation) {
		      case '+':
		        System.out.println(a+b);
		        break;
		      case '-':
		        System.out.println(a-b);
		        break;
		      case '*':
		        System.out.println(a*b);
		        break;
		      case'÷':
		        System.out.println(a/b);
		        break;
	}
	}
		    
		    	
		    }
