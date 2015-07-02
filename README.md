# java
package rj;

abstract class abstrac {
	abstract void disp();
}
class sub extends abstrac
{
	void disp()
	{
		System.out.print("welcome");
	}
	
	public static void main(String args[])
	{

abstrac b1=new sub();
	b1.disp();
}
}



