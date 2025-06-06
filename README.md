import java.util.Scanner;
public class Schedulejobdaily 
{
	public static void main(String[] args) 
		{
			Scanner scan=new Scanner(System.in);
			System.out.println("Enter daily scheduled time in hour");
			int hour=scan.nextInt();
			if(hour>9 && hour<=10)
				{
					System.out.println("Hello World");
				}
			else 
				{
					System.out.println(" ");
				}
		}
}
