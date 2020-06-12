# assignmentpsuedocode
package week1.day2;

public class Oddindextouppercase {

	public static void main(String[] args) {
		String test ="changeme" ;
		 int i;
		 System.out.println(test.length());
		
		for(i=0;i<test.length();i++) {
		  if(i%2!=0) {
			   
			  System.out.println(test.toUpperCase()); 
			  
		 }
		   else {
			   System.out.println(test.charAt(i));


		 }
       
	}
}
}
