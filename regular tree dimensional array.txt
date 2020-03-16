package arrays;
import java.util.Scanner;
public class Regthree {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner scan= new Scanner(System.in);
		int a[][][]= new int[2][2][3];
		for(int i=0;i<a.length;i++) {
			for(int j=0;j<a[i].length;j++) {
				
				for(int k=0;k<a[i][j].length;k++) {
					
					System.out.print("Enter the marks of"+(i+1)+"school"+" " +(j+1) +"class"+" "+(k+1)+" "+ "school");
					a[i][j][k]= scan.nextInt();	
				}
				
					}
			}
			
		System.out.print(" The marks of the students is");
		
		for(int i=0;i<a.length;i++) {
			for(int j=0;j<a[i].length;j++) {
				
				for(int k=0;k<a[i][j].length;k++) {
					
					System.out.print(a[i][j][k]+" ");
					
				}
				System.out.println();
				}
			System.out.println();
				}
		
		}

	}


