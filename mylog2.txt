package com.login;

public class Client {
		
		static int factorial( int n ) {
	        if (n != 0)  // termination condition
	            return n * factorial(n-1); // recursive call
	        else
	            return 1;
	    }

	    public static void main(String[] args) {
	        int number = 4, result;
	        result = factorial(number);
	        System.out.println(number + " factorial = " + result);
	    }
	}
//		int num=3;
//		int fact= 1;
//		
//		
//		for (int i = num; i >0; i--) {
//			
//			
//			fact=fact*i;
//			
//		}
//		
//		System.out.println(fact);