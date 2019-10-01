# username
import java.util.Random;
import java.util.Scanner;



	

	public static void main(String[] args) {
		Scanner scan = new Scanner(System.in);
		String name = new String();
    name = JOptionPane.showDialogue("Enter your name: ");
		String lastName = new String();
    lastName = JOptionpane.showDialogue("Enter your last name: ");
		String s = name.substring(0,1);
		String s1 = s.toLowerCase();
		String t = lastName.substring(0,5);
		String t1 = t.toLowerCase();
		Random r = new Random();
		int n = r.nextInt(10);
		int p = r.nextInt(10);
		System.out.println(s1 + t1 + n + p);

		
		
		

	}

}
