public class ReverseArray {

	public static void main(String[] args) {
		int arr[] = new int[] { 1, 2, 3, 4, 5, 6, 7, 8, 9 };
		int n = arr.length;

		for (int i = 0; i < n / 2; i++) {			//we need to divide into two equal halfs in loop count
			int temp = arr[i];				//swap accordingly using n-1(last index) to 0(first index)
			arr[i] = arr[n - i - 1];			// if i=0,n=last ele   =>  if i=1,n=last but 1 ele => and so on
			arr[n - i - 1] = temp;
		}
		for (int i = 0; i < n; i++) {
			System.out.print(arr[i]);
			if (i != n - 1) {
				System.out.print(", ");
			}
			if (i == n - 1) {
				System.out.print(".");
			}

		}
	}
}
