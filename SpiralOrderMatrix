import java.io.*;
import java.util.*;
public class SpiralTraverseMatrix {
	public static void main(String args[]) throws IOException
	{
		System.out.println("Hello world!!");
		Scanner sc=new Scanner(new BufferedReader(new InputStreamReader(System.in)));
		int m,n;
		m=sc.nextInt();
		n=sc.nextInt();
		int array[][]=new int[m][n];
		for(int i=0;i<m;i++)
		{
			for(int j=0;j<n;j++)
			{
				array[i][j]=sc.nextInt();
			}
		}
		int flag=0;
		int ii=0,ji=0,ifi=m-1,jfi=n-1;
		while(ii<=ifi && ji<=jfi)
		{
			if(flag==0)
			{
				for(int j=ji;j<=jfi;j++)
				{
						System.out.println(array[ii][j]);
				}
				ii++;
				flag=1;
			}
			else if(flag==1)
			{
				for(int i=ii;i<=ifi;i++)
				{
					System.out.println(array[i][jfi]);
				}
				jfi--;
				flag=2;
			}
			else if(flag==2)
			{
				for(int j=jfi;j>=ji;j-- )
				{
					System.out.println(array[ifi][j]);
				}
				ifi--;
				flag=3;
			}
			else if(flag==3)
			{
					for(int i=ifi;i>=ii;i--)
					{
						System.out.println(array[i][ji]);
					}
					ji++;
					flag=0;
			}
			
		}
	}

}
