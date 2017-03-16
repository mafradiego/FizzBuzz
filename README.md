# FizzBuzz
public class FizzBuzz {

		public static void main (String) [] args) {


		int n = 1;


		while (n<= 100) {
			if ((n%3 == 0) || (n%5 ==0)) {
				if (n%3 == 0) {
				System.out.print("Fizz");
				}
				if (n%5 == 0) {
				System.out.print("Buzz");
				}
				System.out.println ();
				}
				else {
				System.out.println(n);
				}
				n = n + 1;
			}
			System.out.println("Acabou...!");
		}
	}
