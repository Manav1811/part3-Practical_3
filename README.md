# part3-Practical_3

package part3;

import java.util.*;

interface P {
	void fun();
}

interface P1 extends P {
	void f1();
}

interface P2 extends P {
	void f2();
}

interface P12 extends P1, P2 {
	void f12();
}

class Exercise implements P12 {
	public void fun()
	{
	 System.out.println("HI");
	}

	public void f1()
	{
	 System.out.println("My name");
	}

	public void f2()
	{
	 System.out.println("is");
	}

	public void f12()
	{
	 System.out.println("Manav");
	}
}

public class Practical_3 {
	public static void main(String[] args) {
		// prepared by 21CE063-Manav Luhar
		Exercise obj = new Exercise();
		obj.fun();
		obj.f1();
		obj.f2();
		obj.f12();
	}
}


