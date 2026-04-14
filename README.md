ample/Main.java‎
+11
Lines changed: 11 additions & 0 deletions
Original file line number	Diff line number	Diff line change
@@ -0,0 +1,11 @@
package org.example;
public class Main {
    public static void main(String[] args) {
        Produto p1 = new Produto("TV", 1500);
        p1.exibirInfo();
        Produto p2 = new Produto("Xbox", 2000);
        p2.exibirGarantia();
    }
}
