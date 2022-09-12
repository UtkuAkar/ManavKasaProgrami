# ManavKasaProgrami
ManavKasaProgrami


import java.util.Scanner;
public class manav {
    public static void main(String[] args) {


        double armut = 2.14 , elma = 3.67 , domates = 1.11 , muz = 0.95 , Patlican = 5.00 ;
        double kg, toplam_tutar;

        Scanner input = new Scanner(System.in);

        System.out.println("Armut kaç kilo : ");
        kg = input.nextDouble();
        double tutar1 = armut * kg;

        System.out.println("Elma kaç kilo : ");
        kg = input.nextDouble();
        double tutar2 = elma * kg;

        System.out.println("Domates kaç kilo : ");
        kg = input.nextDouble();
        double tutar3 = domates * kg;

        System.out.println("Muz kaç kilo : ");
        kg = input.nextDouble();
        double tutar4 = muz * kg;

        System.out.println("Patlıcan kaç kilo : ");
        kg = input.nextDouble();
        double tutar5 = Patlican * kg;
        
        toplam_tutar = tutar1+tutar2+tutar3+tutar4+tutar5;
        
        System.out.println("toplam tutar : "+toplam_tutar);
    }
}
