# Test1
specificValue
import java.util.Arrays;

public class SpecificValue {

	public static boolean contains(int[] xyz, int item) {
		for (int x : xyz) {
			if (item == x) {
				return true;
			}
		}
		return false;
	}
	public static void main(String[] args) {
		int[] myerica_array1 = {
				85, 82, 72, 45, 55, 35, 78, 89, 67};
		
		System.out.println(contains(myerica_array1, 15));
		System.out.println(contains(myerica_array1, 45));
	}
}
