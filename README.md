# Find-integer-and-remainder-in-java.
Find integer and remainder in java.
import java.util.Scanner;
public class ChiaHaiSo {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Nhập vào số thứ nhất: ");
        int num1 = scanner.nextInt();
        System.out.println("Nhập vào số thứ hai: ");
        int num2 = scanner.nextInt();
        int phanNg = num1 / num2;
        int phanDu = num1 % num2;
        System.out.println("Phần nguyên là: " + phanNg);
        System.out.println("Phần dư là: " + phanDu);
    }
}
