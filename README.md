class A
{
	int a;
	A()
	{
		this(5);
		System.out.println("Im default constructor");
	}
	A(int a)
	{
		
		System.out.println("Hello");
	}
}

class Jala 
{
	public static void main(String[] args){
			 A b = new A();
	}
}
