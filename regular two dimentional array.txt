package arrays;

import java.util.Scanner;
public class Regtwo {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner scan = new Scanner(System.in);
		int a[][]=  new int [3][5];
		for(int i=0;i<a.length;i++) {
			for(int j=0;j<a[i].length;j++) {
				
				
				System.out.print("Enter the marks of" +(i+1) +"class"+" "+(j+1)+" "+ "school");
				a[i][j]= scan.nextInt();
			}
			
			
		}
		
		System.out.print(" The marks of the students is");
		
		for(int i=0;i<a.length;i++) {
			for(int j=0;j<a[i].length;j++) {
				
				
				System.out.print(a[i][j]+" ");

			}
			
			System.out.println();

			
			}
		

	}

}
