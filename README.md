//Class creation
class Man{
	String name;
	public static void details(String name)//method and its signature
	{
		System.out.println("Man name is: " + name);
	}
}
public class Jala {

	public static void main(String[] args) {
		
		Man m1 = new Man();//object creation
		m1.details("Sai");

	}

}
