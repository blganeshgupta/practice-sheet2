package arrays;
import java.util.Scanner;
public class jagged3d {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		Scanner next=new Scanner(System.in);
		int [][][]a= new int[2][][];
		  a[0]=new int[2][];
		  a[1]=new int[3][];
		  a[0][0]=new int[2];
		  a[0][1]=new int[3];
		  a[1][0]=new int[4];
		  a[1][1]=new int[4];
		  a[1][2]=new int[6];
		  for(int i=0;i<a.length;i++) {
			  for(int j=0;j<a[i].length;j++) {
				  for(int k=0;k<a[i][j].length;k++) {
					
					  
					  System.out.print("Enter the marks of"+(i+1)+"school"+" "+(j+1)+"class"+" "+(k+1)+"student");
					  
					  a[i][j][k]=next.nextInt(); 	
				  }
					  
				  }
				    
			  }
		  
		  System.out.print("marks of the students are:");
		  
		  for(int i=0;i<a.length;i++) {
			  for(int j=0;j<a[i].length;j++) {
				  for(int k=0;k<a[i][j].length;k++) {
					
					  
					  System.out.print(a[i][j][k]+" ");
		  }
				
				  
				  System.out.println( );
			  }
			  
			  
			  System.out.println( );
			  
				  }
		  
		  
		  }
		
		
		

	}


