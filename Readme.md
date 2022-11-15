public class Main {
    public static void main(String[] args) {
        int amount = 2305;
        int amountOneMile = 20;
        int bonus = amount / amountOneMile;

        System.out.println("Стоимость билета=" + amount);
        System.out.println("Стоимость одной мили=" + amountOneMile);
        System.out.println("Итоговое количество миль:" + bonus);
    }
}