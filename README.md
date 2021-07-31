


public class Main {
    public static void main(String[] args) {
        int treshold = 1000;
        int topUpAmount = 1400;
        int currentBalance = 300;

        int bonus;
        if (topUpAmount > treshold) {
            bonus = topUpAmount / 100 * 1;
        } else {
            bonus = 0;
        }

        int total = currentBalance + topUpAmount + bonus;
        System.out.println(total);

    }
}
