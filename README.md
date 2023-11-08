# primenumber
public class prinmenumber {
	public static boolean isprime(int num)
	{
		int count=0;
	   for(int i=1;i<=num;i++)
	   {
		 if(num%i==0)
		 {
			 count++;
		 }
	   }
	   if(count==2)
	   {
		   return true;
	   }
		return false;
	}
public static void main(String[] args) {
//	if(isprime(3))
//	{
//		System.out.println("its a prime nyumber");
//	}
//	else
//	{
//		System.out.println("its not a prime number");
//	}
	int c=2;
	int count=0;
	for(int i=1;i<=10;i++)
	{
		if(isprime(i))
		{
			count++;
			if(count==c)
			{
			System.out.println(i);
			}
		}
	}
}
}
