# codewithmaheshshukla
java pattern 4321 4321 4321 4321
import java.util.Scanner;

public class number3 {

public static void main (String[] args) {
		
		//4321
		//4321
		//4321
		//4321
		Scanner S=new Scanner(System.in);
		int n;
		n=S.nextInt();
		
		int i=1;
		int p=n;
		while(i<=n)
		{
			int j=1;
			p=n;
			while(j<=n)
			{
			  System.out.print(p);
			  p--;
			  j++;
			}
			System.out.println();
			i++;
			
		}
		
		
	}

}
