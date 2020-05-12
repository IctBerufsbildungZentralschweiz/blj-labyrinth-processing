# Arrays

Unter einem Array man eine Liste oder einen Container, der in der Lage ist, mehrere Werte oder Objekte vom gleichen Typ aufzunehmen. Man kann sich ein Array auch wie eine Kommode mit mehreren Schubladen vorstellen und in jede der Schubladen kann ein Wert abgelegt werden. Dabei erhält jede Schublade eine Etikette, damit sie eindeutig identifiziert werden kann, den sogenannten _Index_.

Im folgenden Beispiel wird ein Array mit 3 Elementen deklariert (also eine "Kommode mit 3 Schubladen"). Im ersten Array-Element wird die Zahl 15 abgelegt, im zweiten Element die Zahl 3 und im dritten Element die Zahl 11. Zu beachten ist dabei, dass das erste Element über den Index [0] angesprochen wird, das zweite über den Index [1] und das dritte über den Index [2]. Die Indexierung ist also 0-basiert.

```java
    int[] numbers = new int[3];
    numbers[0] = 15;
    numbers[1] = 3;
    numbers[2] = 11;
```

Das Auslesen des Arrays erfolgt ebenfalls über den Index. Beachte auch hier, das die Indexierung bei 0 beginnt. Das dritte Element wird also über den Index [2] angesprochen.

```java
    int number1 = numbers[0];
    println(number1);

    int number2 = numbers[1];
    println(number2);

    int number3 = numbers[2];
    println(number3);
```

Die Anzahl Elemente eines Arrays kann über die Eigenschaft `length` ermittelt werden. Dies ist praktisch, da so mit einer `for`-Schleifen über alle Elemente eines Arrays iteriert werden kann.

```java
    int[] numbers = new int[3];
    numbers[0] = 15;
    numbers[1] = 3;
    numbers[2] = 11;

    for (int i = 0; i < numbers.length; i++) {
        println(numbers[i]);
    }
```

## Zweidimensionale Arrays

Ein zweidimesionales Array kann man sich wie eine Tabelle vorstellen. Im folgenden Beispiel wird ein Array erstellt mit zwei "Zeilen" und drei "Spalten".

```java
    int[][] numbers = new int[2][3];
    numbers[0][0] = 11; // Wert 11 in Zeile 1, Spalte 1 der "Tabelle" ablegen
    numbers[0][1] = 12; // Wert 12 in Zeile 1, Spalte 2 der "Tabelle" ablegen
    ...
    numbers[1][2] = 23; // Wert 23 in Zeile 2, Spalte 3 der "Tabelle" ablegen 
```

