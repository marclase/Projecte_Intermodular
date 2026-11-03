# Condicionals i bucles

## Condicional if

Serveix per a fer una cosa **només si** es compleix una condició.

```java
int nota = 7;

if (nota >= 5) {
    System.out.println("Aprovat");
} else {
    System.out.println("Suspés");
}
```

### Comparadors

| Símbol | Vol dir |
|--------|---------|
| `==` | igual |
| `!=` | diferent |
| `>` | major |
| `<` | menor |
| `>=` | major o igual |
| `<=` | menor o igual |

## Bucle for

Repeteix una cosa un nombre de vegades.

```java
for (int contador = 1; contador <= 5; contador++) {
    System.out.println(contador);
}
```

## Bucle while

Repeteix mentre la condició siga certa.

```java
int contador = 1;

while (contador <= 5) {
    System.out.println(contador);
    contador++;
}
```

!!! danger "Perill"
    Si t'oblides de fer `contador++` en el `while`, el bucle **no acaba mai**.

!!! warning "Compte"
    Per a comparar s'usa `==`. Un sol `=` és per a **guardar** un valor.

!!! success "Recorda"
    `if` per a decidir, `for` quan sabem quantes vegades, `while` quan no ho sabem.

??? question "Què mostra el for de dalt?"
    Els números de l'1 al 5, cada un en una línia.
