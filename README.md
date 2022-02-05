# programm1.java
programm
import java.util.Scanner;
public class Calculator
{

	public static void main(String[] args) 
	{
		Scanner scan = new Scanner(System.in);
		double a;
		double b;
		double result = 0;
		System.out.println("enter the numbers");
		    a=scan.nextDouble();
		    b=scan.nextDouble();
		    System.out.println("enter the operator('+','-','*','/')");
		    char op = scan.next().charAt(0);
		    
		    switch (op)
		    {
		      case '+':
		      result= a+b;
		      break;
		      
		      case '-':
			      result= a-b;
			      break;
			      
		      case '*':
			      result= a*b;
			      break;
			   
		      case '/':
			      result= a/b;
			      break;
			   
			  default:
				  System.out.println("You enter wrong input");
				  
		            break;
		    }
		    System.out.println("The final result:");
		    
	        System.out.println();
	  
	        // print the final result
	        System.out.println(a + " " + op + " " + b
	                           + " = " + result);
		    
	}

}
