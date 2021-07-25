public class Main {
    public static void main(String[] args) {
        int treshold = 1000;
        int top_up_amount = 1400;
        int current_balance = 300;

        int bonus;
        if (top_up_amount > treshold) {
            bonus = top_up_amount / 100 * 1;
        } else {
            bonus = 0;
        }

        int total = current_balance + top_up_amount + bonus;
        System.out.println(total);

    }
}