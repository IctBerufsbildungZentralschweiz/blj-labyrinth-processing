# Aufgabenblatt 1

## Schreibtischtest

> Der Schreibtischtest ist ein Verfahren, das im Bereich der Softwareentwicklung verwendet wird, um Algorithmen oder Routinen auf Richtigkeit zu prüfen. Der Schreibtischtest wird nicht mit Hilfe eines Rechners durchgeführt, sondern vielmehr im Kopf des Entwicklers.

Quelle: [Wikipedia](https://de.wikipedia.org/wiki/Schreibtischtest)

## Aufgaben

Verwende __keine__ Entwicklungsumgebung und __keinen__ Taschenrechner, sondern löse die Aufgaben im Kopf und schriftlich auf Papier. Drucke dazu das Aufgabenblatt aus.

**Was wird jeweils in der Konsole ausgegeben?**

### Aufgabe 1

```java
    int a = 25;
    println(a);
```

Ausgabe: ___

### Aufgabe 2

```java
    int a = 25;
    int b;
    b = a + 5;
    println(b);
```

Ausgabe: ___

### Aufgabe 3

```java
    String a = "25";
    String b;
    b = a + "5";
    println(b);
```

Ausgabe: ___

### Aufgabe 4

```java
    String a = "25";
    String b;
    b = a + 5;
    println(b);
```

Ausgabe: ___

### Aufgabe 5

```java
   int a = 30;
   if (a + 11 > 40) {
        println("Hallo");
   }
   else {
       println("Welt");
   }
```

Ausgabe: ___

### Aufgabe 6

```java
    Boolean b = true;
    if (b == true) {
        println("Hallo");
    }
    println("Welt");
```

Ausgabe: ___

### Aufgabe 7

```java
    Boolean b = false;
    if (b) {
        println("Hallo");
    }
    println("Welt");
```

Ausgabe: ___

### Aufgabe 8

```java
    Boolean b = false;
    Boolean c = false;
    if (b != c) {
        println("Mehr");
    }
    else {
        println("Weniger");
    }
```

Ausgabe: ___

### Aufgabe 9

```java
    Boolean b = false;
    Boolean c = !b;
    if (c == true) {
        println("Mehr");
    }
    else {
        println("Weniger");
    }
```

Ausgabe: ___

### Aufgabe 10

```java
    Boolean b = true;
    Boolean c = false;
    if (c && b) {
        println("Eins");
    }
    else {
        println("Zwei");
    }
```

Ausgabe: ___

### Aufgabe 11

```java
    Boolean b = true;
    Boolean c = false;
    if (c || b) {
        println("Eins");
    }
    else {
        println("Zwei");
    }
```

Ausgabe: ___

### Aufgabe 12

```java
    int a = 25;
    Boolean b = true;
    Boolean c = false;
    if (a == 25 && b == false) {
        println("Hü?");
    }
    else if (a > 20 && c == false) {
        println("Hä?");
    }
    else {
        println("Hö?");
    }
```

Ausgabe: ___

### Aufgabe 13

```java
    int a = 25;
    Boolean b = true;
    Boolean c = a > 25;
    if (a > 20 && c != b && b || c) {
        println("Hü?");
    }
    else if (a != 25) {
        println("Hä?");
    }
    else {
        println("Hö?");
    }
```

Ausgabe: ___

### Aufgabe 14

```java
    int a = 1;
    while (a < 10) {
        if (a > 0) {
            a++;
        }
        else {
            a--;
        }
    }
    println(a);
```

Ausgabe: ___

### Aufgabe 15

```java
    Boolean b = true;
    while (b == true) {
        a++;
    }
    println(a);
```

Ausgabe: ___

### Aufgabe 16

```java
    int a = 0;
    Boolean b = true;
    int c = 0;
    while (b) {
        if (b && a < 50) {
            a = a + 10;
        }
        else {
            b = false;
        }
        c++;
    }
    println(c);
```

Ausgabe: ___
