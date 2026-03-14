# java-test-0003-final-12170-pratiksha
Final Project Assignment - This repository contains the complete final project code and documentation.
public class BinaryTriangle {
    public static void main(String[] args) {
        int n = 6;

        for (int i = 1; i <= n; i++) {
            int num;

            if (i % 2 == 0) {
                num = 0;
            } else {
                num = 1;
            }

            for (int j = 1; j <= i; j++) {
                System.out.print(num);
                num = (num == 1) ? 0 : 1;  // switch between 1 and 0
            }

            System.out.println();
        }
    }
}
