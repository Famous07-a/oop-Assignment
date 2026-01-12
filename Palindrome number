import java.util.Scanner;

class PalindromeNumber {

    // Method to check palindrome
    static boolean isPalindrome(int x) {

        int original = x;
        int reverse = 0;

        while (x > 0) {
            int digit = x % 10;
            reverse = reverse * 10 + digit;
            x = x / 10;
        }

        if (original == reverse) {
            return true;
        } else {
            return false;
        }
    }

    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int num = sc.nextInt();

        if (isPalindrome(num)) {
            System.out.println("Palindrome number");
        } else {
            System.out.println("Not a palindrome number");
        }
    }
}
