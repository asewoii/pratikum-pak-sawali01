## Pertemuan1
````Pratikum Pak Sawali```` ````Progam java````

```
package fasilkom;

public class FASILKOM {
    
    private static String setNama;
    private static int setNim;
    public String nama;
    private int nim;
    
    public FASILKOM (String nama, int nim) 
        {
            this.nama = nama;
            this.nim = nim;
        }
    
    public String getNama() {
        return this.nama;
    }
    
    public void setNama(String nama) {
        this.nama = nama;
    }
    
    public int getNim() {
        return this.nim;
    }
    
    public void setNim(int nim) {
        this.nim = nim;
    }
    
    public static void main(String[] args) {
         FASILKOM fasilkom = new FASILKOM("Nyoman", 147);
        
        System.out.println("nama saya : " + fasilkom.nama);
        System.out.println("nim saya : " + fasilkom.nim);
    }
    
}
```

## Pertemuan2
````Pratikum Pak Sawali```` ````Progam java````

```
package jayaesport;

public class JayaEsport {

    public static void main(String[] args) {
        //membuat variabel
        String nama, fakultas, kuliah;
        int umur;
        double tinggi__badan;
        float ipk;
        char gender;
        boolean lulus;
        
        //mengisi variabel
        nama = "Nyoman";
        fakultas = "Ilmu Komputer";
        kuliah = "Esa Unggul";
        umur = 19;
        tinggi__badan = 180.9 + 5;
        ipk = 3.9f;
        gender = 'L';
        lulus = true;
        
        //proses
        System.out.println("Nama            = " +nama);
        System.out.println("Fakultas        = " +fakultas);
        System.out.println("Kuliah          = " +kuliah);
        System.out.println("Umur            = " +umur);
        System.out.println("Tinggi Badan    = " +tinggi__badan);
        System.out.println("Ipk             = " +ipk);
        System.out.println("Gender          = " +gender);
        System.out.println("Lulus           = " +lulus);
    }  
    
}
```
