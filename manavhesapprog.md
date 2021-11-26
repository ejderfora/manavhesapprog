```java
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner inp = new Scanner(System.in);

        double armut = 2.14 , elma = 3.67 , domates = 1.11 , muz = 0.95 , patlican = 5 , kg, tutar = 0;

        System.out.print("Armut KG Miktarını Girin: ");
        kg = inp.nextDouble();
        tutar += armut*kg;

        System.out.print("Elma KG Miktarını Girin: ");
        kg = inp.nextDouble();
        tutar += elma*kg;

        System.out.print("Domates KG Miktarını Girin: ");
        kg = inp.nextDouble();
        tutar += domates*kg;

        System.out.print("Muz KG Miktarını Girin: ");
        kg = inp.nextDouble();
        tutar += muz*kg;

        System.out.print("Patlıcan KG Miktarını Girin: ");
        kg = inp.nextDouble();
        tutar += patlican*kg;

        System.out.print("Toplam Tutar: " + tutar);


    }
}
```