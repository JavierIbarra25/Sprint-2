public class main {
    public static void main(String[] args) {

        int llarg = 300;
        int ample1 = 150;
        int profunditat1 = 20;
        int ample2 = 80;
        int profunditat2 = 35;
        int ample3 = ample1 + ample2;

        //Piscina 1

        int AreaPiscina1 = ample1 * llarg;
        int VolumPiscina1 = AreaPiscina1 * profunditat1;
        System.out.println("Valors de la piscina 1 ----- àrea " + AreaPiscina1 + " y volum " + VolumPiscina1);

        //Piscina 2

        int AreaPiscina2 = ample2 * llarg;
        int VolumPiscina2 = AreaPiscina2 * profunditat2;
        System.out.println("Valors de la piscina 2 ----- àrea " + AreaPiscina2 + " y volum " + VolumPiscina2);

        //Piscina 1 i 2

        System.out.println("Valors de les dues piscines ------ " + "ample: " + ample3 + " y llarg: " + llarg);

        int AreaPiscina3 = ample3 * llarg;
        System.out.println("valor del àrea de les dues piscines: " + AreaPiscina3);

        int VolumPisccina3 = VolumPiscina1 + VolumPiscina2;
        System.out.println("valor del volum de les dues piscines: " + VolumPisccina3);

        //Piscines valors intercanviats

        int profunditat = profunditat1;
        profunditat1 = profunditat2;
        profunditat2 = profunditat;

        VolumPiscina1 = AreaPiscina1 * profunditat1;
        VolumPiscina2 = AreaPiscina2 * profunditat2;

        System.out.println("Valors intercambiats de la piscina 1 ----- ample: " + ample1 + ", llarg: " + llarg + ", profunditat " + profunditat1 + ", volum " + VolumPiscina1);
        System.out.println("Valors intercambiats de la piscina 2 ----- ample: " + ample2 + ", llarg: " + llarg + ", profunditat " + profunditat2 + ", volum " + VolumPiscina2);

    }
    }
