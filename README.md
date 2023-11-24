# fauzip12

public class Buaya {
    String jenis = "PRIA";
    String umur = "2 tahun";

    void menyelam() {
        System.out.println(" Buaya " + jenis  + " umur " + umur + " menyelam ");
    }

    void muncul() {
        System.out.println(" Buaya " + jenis  + " umur " + umur + " muncul ");
    }

    public static void main(String[] args) {
        System.out.println("hallo");
        Buaya myBuaya = new Buaya();
        myBuaya.menyelam();
        myBuaya.muncul();
    }
}
