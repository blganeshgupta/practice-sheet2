package arrays;

import java.util.Scanner;
public class Jagged2d {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Scanner scan=new Scanner(System.in);
		int [][]a=new int[2][];
		a[0]=new int[3];
		a[1]=new int[4];
		for(int i=0;i<a.length;i++) {
			for(int j=0;j<a[i].length;j++) {
			
				System.out.print("Enter the marks of"+(i+1)+"class"+" "+(j+1)+"student");
				  a[i][j]=scan.nextInt(); 
			
			}
			
			
			
			}
			
		System.out.print("the marks of the students are : ");
		for(int i=0;i<a.length;i++) {
		
			for(int j=0;j<a[i].length;j++) {
			
				
				
				  System.out.print(a[i][j]+" ");
				
			}
		
			 System.out.println( );
			
		}
		
		 

		}
		
	}

