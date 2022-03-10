# 1

# All Prime Numbers 

<!--
Note - Any content mention below in `<!-- ->` blocks are just comments
to help you fill-up the issue. It won't be visible in the actual issue after
you click on submit.
-->



#### Code you used for Submit/Run operation


```
// Pogram
import java.util.Scanner;
public class Solution {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Scanner sc = new Scanner(System.in);
		int n = sc.nextInt();

		int i = 2;

		while (i <= n) {
			int count = 0;
			int j = 2;
			while (j <= i) {
				if (i % j == 0)
					count++;
				j++;
			}

			if (count == 1) {
				System.out.println(i);
			}
			i++;

		}

//		for (int i = 2; i <= n; i++) {
//			int count = 0;
//			for (int j = 2; j <= i; j++) {
//				if (i % j == 0)
//					count++;
//			}
//			if (count == 1)
//				System.out.println(i);
//		}
	}
}
```

#### Language used for code
java 


#### Expected behavior
<!-- A clear and concise description of what you expected to happen in
contrast with what actually happened. -->
milestone 1 Operator & for loop

#### Screenshots

![all prime](https://user-images.githubusercontent.com/53940939/156886132-fab50fa9-4c33-4b5a-9a17-49d043d4b581.png)

# 2

# Terms Of Ap 

<!--
Note - Any content mention below in `<!-- ->` blocks are just comments
to help you fill-up the issue. It won't be visible in the actual issue after
you click on submit.
-->



#### Code you used for Submit/Run operation


```
// Pogram
import java.util.Scanner;
public class Main {
	
	public static void main(String[] args) {
		Scanner scan = new Scanner(System.in);
		int n = scan.nextInt();
		int i = 1;
		int count = 0;
		while (count < n) {
			int num = (3 * i) + 2;

			if (num % 4 != 0) {

				System.out.print(num + " ");
				count++;
			}

			i++;

//		for(int i = 1 ; i<=n ; i++) {
//			int num = (3*i)+2;
//			if(num%4!=0) {
//				System.out.println(num);
//			}
//			else
// 				continue;
//				
//			
//			
//			
//			System.out.println(num);
		}

	}

}

```

#### Language used for code
java 


#### Expected behavior
<!-- A clear and concise description of what you expected to happen in
contrast with what actually happened. -->
milestone 1 Operator & for loop

#### Screenshots

![ap](https://user-images.githubusercontent.com/53940939/156886182-96d0903e-3e77-4297-b0f4-090236bd550c.png)

# 3

# Reverse of a number

<!--
Note - Any content mention below in `<!-- ->` blocks are just comments
to help you fill-up the issue. It won't be visible in the actual issue after
you click on submit.
-->



#### Code you used for Submit/Run operation


```
// Pogram
import java.util.Scanner;
public class Main {
	
	public static void main(String[] args) {
	Scanner scan = new Scanner(System.in);
		int n = scan.nextInt();

		int rn = 0;
		while (n > 0) {
			rn = rn * 10 + n % 10;
			n = n / 10;

		}

		System.out.println(rn);

	}

}


```

#### Language used for code
java 


#### Expected behavior
<!-- A clear and concise description of what you expected to happen in
contrast with what actually happened. -->
milestone 1 Operator & for loop

#### Screenshots

![reverse](https://user-images.githubusercontent.com/53940939/156886228-6d7e4e29-8a7e-4290-ac49-0559aa79c310.png)

# 4

# Binary to decimal

<!--
Note - Any content mention below in `<!-- ->` blocks are just comments
to help you fill-up the issue. It won't be visible in the actual issue after
you click on submit.
-->



#### Code you used for Submit/Run operation


```
// Pogram
import java.util.Scanner;
public class Main {
    
  public static void main (String[] args)  
    {
Scanner scan = new Scanner(System.in);

		int n = scan.nextInt();
        int decimal = 0 , pow = 1;
       
       while(n>0){
           int last = n%10;
           
           decimal = decimal + last * pow;
           
           pow = pow * 2;
           
           n = n/10;
       }
       System.out.print(decimal);

		

	}
}
      


```

#### Language used for code
java 


#### Expected behavior
<!-- A clear and concise description of what you expected to happen in
contrast with what actually happened. -->
milestone 1 Operator & for loop

#### Screenshots

![b to d](https://user-images.githubusercontent.com/53940939/156886285-1eb9d6bc-b13a-475d-b77f-a5530da0b814.png)


# 5

# Decimal To Binary

<!--
Note - Any content mention below in `<!-- ->` blocks are just comments
to help you fill-up the issue. It won't be visible in the actual issue after
you click on submit.
-->



#### Code you used for Submit/Run operation


```
// Pogram
import java.util.Scanner;
public class Main {
	
	public static void main(String[] args) {
		// Write your code here
Scanner scan = new Scanner(System.in);

		int n = scan.nextInt();

		int binary[] = new int[40];

		int index = 0;
		if (n==0)
	    {
	        System.out.print("0");
	        return;
	    }
		while (n > 0) {
			binary[index++] = n % 2;
			n = n / 2;
		}
		for (int i = index - 1; i >= 0; i--) {
			System.out.print(binary[i]);
		}

	}
}

```

#### Language used for code
java 


#### Expected behavior
<!-- A clear and concise description of what you expected to happen in
contrast with what actually happened. -->
milestone 1 Operator & for loop

#### Screenshots

![d to c](https://user-images.githubusercontent.com/53940939/156886343-79235f59-1e1d-4688-9551-1e995e857c49.png)


![WhatsApp Image 2022-03-05 at 7 26 32 PM](https://user-images.githubusercontent.com/53940939/156886447-a9a08fab-f867-431a-bcf4-48f95c0d460b.jpeg)



