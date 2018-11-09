# ArraysSwitchElements
ArraysSwitchElements
import java.util.Arrays;

public class ArraysSwitchElements {
	public static void main(String[] args) {
		
		int[] i= {5,4,3,2}; //{2,4,3,5}
		//do_switch(i);
		System.out.println(Arrays.toString(do_switch(i)));
	}
		
	/*
	 * Switch the last element in 
	 * an array with the first and return the array.
	 */
	public static int[] do_switch(int[] i) {
      
		int temp=i[0];
			i[0]=i[i.length-1];
			i[i.length-1]=temp;	
		
		return i;
			}
		}

