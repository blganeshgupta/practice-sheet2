package arrays;
import java.util.Scanner;
public class Jagged1d {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner scan= new Scanner(System.in);
		int []a=new int[5];
		for(int i=0;i<a.length;i++) {
		
			System.out.print("Enter the marks of"+(i+1)+ " student"+" ");
			
			a[i]=scan.nextInt(); 
		
		}
		 
		
		System.out.print("Enter the marks of (i+1) student");
		for(int i=0;i<a.length;i++) {
			
			
			System.out.print(a[i]+" ");
			System.out.println( );
		}
		
		
		System.out.println( );
	}

}
