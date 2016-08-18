# substring
import java.util.Scanner;

public class Substring {
	public static void main(String[] args) {

		Scanner a = new Scanner(System.in);
		System.out.println("enter the first string");
		String s1 = a.next();
		System.out.println("enter the second string");
		String s2 = a.next();
		System.out.println(s1.indexOf(s2));

	}

}
