# Variables i dades

Una **variable** és un lloc de la memòria on guardem una dada. Cada variable té un **tipus** i un **nom**.

## Tipus més usats

| Tipus | Guarda | Exemple |
|-------|--------|---------|
| `int` | Nombres enters | `5` |
| `double` | Nombres amb decimals | `3.14` |
| `boolean` | Veritat o fals | `true` |
| `char` | Una lletra | `'a'` |
| `String` | Text | `"Hola"` |

## Exemple

```java
int edat = 18;
double altura = 1.75;
String nom = "Marc";
boolean estudiant = true;
```

## Llegir dades del teclat

Per a preguntar una dada a l'usuari fem servir `Scanner`:

```java
import java.util.Scanner;

public class DobleNumero {
    public static void main(String[] args) {
        Scanner entrada = new Scanner(System.in);

        System.out.println("Escriu un numero:");
        int numero = entrada.nextInt();
        int doble = numero * 2;

        System.out.println("El doble es " + doble);
    }
}
```

## Consells per als noms

- Posa noms que expliquen què guarden (`numero`, `edat`, `nom`).
- No comences amb un nombre.
- Sense espais.

!!! tip "Consell"
    Si poses bons noms a les variables, el codi s'entén molt millor.

!!! warning "Compte"
    Per a guardar text es fa servir `String` amb la **S majúscula**.

!!! info "Operadors"
    Els més usats són `+`, `-`, `*`, `/` i `%` (el que sobra de dividir).
