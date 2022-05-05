```java
import java.util.Scanner;
public class hiphes {
    public static void main (String [] args) {
        double x, y, z;
        Scanner giris = new Scanner (System.in);
        System.out.print("1. Kenarı Girin :");
        x = giris.nextInt();
        System.out.print("2. Kenarı Girin :");
        y = giris.nextInt();
        
        z = Math.sqrt ((x*x) + (y*y));
        System.out.println ("Hipotenüs :" + z);


    }
}
```

