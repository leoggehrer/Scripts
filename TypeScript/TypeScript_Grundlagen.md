# TypeScript

## TS Überblick

Übermenge von JavaScript
Streng typisiert
Compiletime-Errors
Objektorientiert
Gute Toolunterstützung

![Folie 1 Bild 3](img/slide1_img3.jpeg)

---

## Edit – Build - Run

Codieren in TS
Compilieren (transpile) in JS ES5 oder JS ES6
Ausführen im Browser
Debuggen auf Basis von TS

![Folie 2 Bild 7](img/slide2_img7.jpeg)

![Folie 2 Bild 8](img/slide2_img8.png)

---

## Simples TS-Program

Definition einer einfachen Funktion
Aufruf im „Hauptprogramm“

![Folie 3 Bild 5](img/slide3_img5.png)

---

## Build and run

![Folie 4 Bild 5](img/slide4_img5.png)

---

## Transpiliertes js-Programm

Ident ➔ gültiger JS-Code ist auch gültiger TS-Code

![Folie 5 Bild 6](img/slide5_img6.png)

---

## Gültigkeitsbereich var

var (JS ES5) ➔ Innerhalb der Funktion

![Folie 6 Bild 4](img/slide6_img4.png)

![Folie 6 Bild 5](img/slide6_img5.png)

---

## Gültigkeitsbereich let

let (JS ES6) ➔ Blockorientiert
Erkennt Compilerfehler
Compiliert aber in gleiche JS-Datei wie vorher

![Folie 7 Bild 4](img/slide7_img4.png)

---

## Variablendeklarationen

Explizite Typangabe oder Typinferenz

![Folie 8 Bild 3](img/slide8_img3.png)

---

## Typsicherheit

![Folie 9 Bild 3](img/slide9_img3.png)

---

## Aufzählungen enum

- Erzeugter JS-Code

![Folie 10 Bild 4](img/slide10_img4.png)

![Folie 10 Bild 5](img/slide10_img5.png)

---

## Typ herleitbar ➔ Intellisense

Sonst: Typeassertion (C# Cast)
Auch mit <> möglich

![Folie 11 Bild 8](img/slide11_img8.png)

![Folie 11 Bild 9](img/slide11_img9.png)

![Folie 11 Bild 10](img/slide11_img10.png)

---

## Übung Types

Typsicherheit ausprobieren
string, number, boolean, any

---

## Arrays

![Folie 13 Bild 3](img/slide13_img3.jpeg)

![Folie 13 Bild 4](img/slide13_img4.jpeg)

![Folie 13 Bild 5](img/slide13_img5.jpeg)

---

## Tuple

![Folie 14 Bild 3](img/slide14_img3.png)

![Folie 14 Bild 4](img/slide14_img4.jpeg)

---

## Beispiel PupilCounter

![Folie 15 Bild 4](img/slide15_img4.png)

![Folie 15 Bild 5](img/slide15_img5.png)

---

## Functions

Ähnlich wie in C# und Java
Typdefinition optional

![Folie 16 Bild 4](img/slide16_img4.jpeg)

![Folie 16 Bild 5](img/slide16_img5.jpeg)

---

## Funktionen sind normale Elemente

- In Variablen speicherbar
- Als Parameter übergebbar

![Folie 17 Bild 3](img/slide17_img3.jpeg)

---

## Beispiel: Summe mit automatischem parse

![Folie 18 Bild 3](img/slide18_img3.jpeg)

---

## Optionale Parameter

Überprüfen mit undefined


![Folie 19 Bild 3](img/slide19_img3.jpeg)

---

## Komfort wie in C#

- Funktionen als Parameter übergeben
- LambdaExpressions heißen ArrowFunctions

![Folie 20 Bild 3](img/slide20_img3.png)

![Folie 20 Bild 4](img/slide20_img4.png)

---

## Klassen

- Fields
- Functions in Klassen sind Methoden
- Standard public

![Folie 21 Bild 3](img/slide21_img3.png)

---

## Klassen - Verwendung

Fields werden später in Properties eingepackt

![Folie 22 Bild 6](img/slide22_img6.png)

---

## Wie viele Jahre ist der Schüler alt?

Gewünschte Ausgabe des Programms

![Folie 23 Bild 3](img/slide23_img3.png)

---

## Alternativ im Browser

![Folie 24 Bild 3](img/slide24_img3.png)

---

## Constructor, optionale Parameter

- Constructor wir in C#/Java
- Optionale Parameter am Schluss der Parameterliste

![Folie 25 Bild 4](img/slide25_img4.png)

---

## Kapselung der fields

Get/Set-Methode wie in Java

![Folie 26 Bild 4](img/slide26_img4.png)

---

## Definition der fields im Constructor

Sehr kompakter Code

![Folie 27 Bild 7](img/slide27_img7.png)

---

## Properties in TS

- Kapselung in Getter/Setter wie in C#
- Validierung, Converter, …
- Intuitive Verwendung

![Folie 28 Bild 3](img/slide28_img3.png)

![Folie 28 Bild 4](img/slide28_img4.png)

---

## Compiler liefert Fehlermeldung

- AccessModifiers gibt es erst ab ES5 (können alle relevanten Browser)
- tsc compiliert per default gegen ES3
- Compiler konfigurieren (Target ES5)

![Folie 29 Bild 3](img/slide29_img3.png)

![Folie 29 Bild 4](img/slide29_img4.png)

---

## TS-Modul (nicht Angular Module)

Klasse in eigene Datei und „export“

![Folie 30 Bild 5](img/slide30_img5.png)

---

## Verwendung über import

![Folie 31 Bild 4](img/slide31_img4.png)

---

## Vererbung ist natürlich auch möglich

![Folie 32 Bild 3](img/slide32_img3.png)

---
