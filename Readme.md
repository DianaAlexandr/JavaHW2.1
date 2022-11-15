public class Main {
    public static void main(String[] args) {
    
        int amount = 2305; // стоимость билета в рублях
        int amountOneMile = 20; // стоимость одной мили в рублях
        int bonus = amount / amountOneMile; // расчет начисления миль, за каждые 20 рублей, потраченных на билет

        System.out.println("Стоимость билета=" + amount);
        System.out.println("Стоимость одной мили=" + amountOneMile);
        System.out.println("Итоговое количество миль:" + bonus);
        
    }
}
