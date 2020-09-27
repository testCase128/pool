# pool
## pool
![original](https://user-images.githubusercontent.com/47565961/94369297-b0a77f80-010a-11eb-80d4-8a89050d1078.jpg)



import java.util.Scanner;

**public class WeightedAverages {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int n = Integer.parseInt(scanner.nextLine());
        for (int i = 0;i < n; i++){
            String[] str = scanner.nextLine().split(" ");
            double num = Double.parseDouble(str[0]) * 2;
            double num2 = Double.parseDouble(str[1]) * 3;
            double num3 = Double.parseDouble(str[2]) * 5;
            double result = (num + num2 + num3) / (2 + 3 + 5);
            System.out.printf("%.1f \n",result);
        }
    }
}**
