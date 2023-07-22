package org.conditional;
import java.util.Scanner;
public class Demo {
	static Scanner s=new Scanner(System.in);
	public static void main(String[] args) {
		System.out.println("enter the vowels");
		char ch=s.next().charAt(0);
		if(ch=='a'||ch=='A'||ch=='e'||ch=='E'||ch=='i'||ch=='I'||ch=='o'||ch=='O'||ch=='u'||ch=='U')
		{
			System.out.println("this is vowel");
		}
		else {
			System.out.println("this is consonant");
		}
	

	}

}
