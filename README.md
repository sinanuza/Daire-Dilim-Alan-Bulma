# Daire-Dilim-Alan-Bulma
www.patika.dev




        import java.util.Scanner;

        public class daire {
        public static void main(String[] args) {
        int r;
        double a;
        double pi=3.14;

        System.out.println("Lutfen r yari capini giriniz:");
        Scanner cap =new Scanner(System.in);
        r=cap.nextInt();

        System.out.println("Lutfen dilim acisini giriniz:");
        Scanner acı =new Scanner(System.in);
        a=acı.nextDouble();
        double dilimalan=(pi*(r*r)*a)/360;

        System.out.println("Dilim Alaniniz:"+dilimalan);
    }
}
