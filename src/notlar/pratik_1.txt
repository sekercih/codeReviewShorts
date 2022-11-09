package shortvideolarserisi;

public class Pratik_1 {
    public static void main(String[] args) {
        // todo Bir method icerisinde en yuksek sayiyi bulan method?

        int[] sayilar = {1250, 7500, 3500, 6700, 8880, 1310};

        int enbuyukSayi = Integer.MIN_VALUE;

        for (int sayi : sayilar) {
            if (sayi > enbuyukSayi) {
                enbuyukSayi = sayi;
            }
        }
        System.out.println("enbuyukSayi = " + enbuyukSayi);
    }
}
