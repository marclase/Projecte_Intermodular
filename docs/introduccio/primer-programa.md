# El primer programa

## Hola món

El primer programa que es fa sempre és mostrar un text per pantalla.

```java
public class HolaMon {
    public static void main(String[] args) {
        System.out.println("Hola món!");
    }
}
```

## Què vol dir cada part

- `public class HolaMon`: el nom de la classe. Ha de coincidir amb el nom del fitxer.
- `public static void main`: ací comença el programa.
- `System.out.println`: mostra un text i fa un salt de línia.

## Compilar i executar

Des de la terminal:

```bash
javac HolaMon.java
java HolaMon
```

L'eixida és:

```text
Hola món!
```

!!! warning "Compte"
    Java distingeix entre **majúscules i minúscules**. `System` no és el mateix que `system`.

!!! danger "Error típic"
    Si t'oblides del `;` al final de la línia, el programa **no compila**.

!!! example "Prova-ho"
    Canvia el text per el teu nom i torna a executar el programa.

??? question "Per què el fitxer es diu HolaMon.java?"
    Perquè en Java el nom del fitxer ha de ser igual que el de la classe pública.
