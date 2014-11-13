TugasProcedureMenghitungLuass
=============================
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package id.blits.menghitungluas;

/**
 *
 * @author Hp
 */
public class MainMenu {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        
       System.out.println("<<<===>>> MENGHITUNG LUAS <<<===>>>"+"\n");
        PersegiPanjang pita = new PersegiPanjang();
        pita.panjang=15;
        pita.lebar=10;
        pita.tampilPersegiPanjang();
        
        Lingkaran phita= new Lingkaran();
        phita.jarijari= 2 ;
        phita.tampilLingkaran();
        
        Segitiga nurpita = new Segitiga();
        nurpita.tinggi=10;
        nurpita.tampilSegitiga();
    
    }
    
}
