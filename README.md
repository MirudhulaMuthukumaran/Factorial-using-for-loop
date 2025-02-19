# Factorial-using-for-loop
class Factorial {
    public static void main(String[] args) {
        int number = 5; // You can change this value to test with other numbers
        long factorial = 1;

        for (int i = 1; i <= number; i++) {
            factorial *= i;
        }

        System.out.println("The factorial of " + number + " is " + factorial);
    }
}

OUTPUT:
The factorial of 5 is 120
