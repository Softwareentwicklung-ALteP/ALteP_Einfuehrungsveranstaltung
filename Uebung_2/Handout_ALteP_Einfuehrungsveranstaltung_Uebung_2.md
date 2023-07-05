# ALteP Einführung

Die Aufgaben sind eine Auswahl der Aufgaben der C#-Belege. Hier sollen die Aufgaben mit Python gelöst werden.

## 1. The "Pythonic" Way
$$ \sum^{X}_{n=0} {n} $$
1. Entwickeln Sie eine Funktion, welche das Ergebnis von obiger Gleichung berechnet. Der Wert X soll an diese Funktion übergeben werden. Nutzen Sie for-Schleifen und verzichten Sie auf Libraries.
2. Eine zweite Funktion soll nach dem gleichen Prinzip nur die Summe der Primzahlen aus dem vorgegebenen Bereich (n, X) berechnen.
3. Vereinfachen Sie die Funktionen durch die Verwendung Python-Eigener Methoden und der Library *SymPy*.


## 2. Kontrollfluss

Im Gregorianischen Kalender wird das Schaltjahr wie folgt [definiert](https://de.wikipedia.org/wiki/Schaltjahr#Gregorianischer_Kalender):

 - *"Die durch 4 ganzzahlig teilbaren Jahre sind, abgesehen von den folgenden Ausnahmen, Schaltjahre."*
 - *"Säkularjahre, also die Jahre, die ein Jahrhundert abschließen (z. B. 1800, 1900, 2100 und 2200) sind, abgesehen von der folgenden Ausnahme, keine Schaltjahre."*
 - *"Die durch 400 ganzzahlig teilbaren Säkularjahre, zum Beispiel das Jahr 2000, sind jedoch Schaltjahre."*

1. Bestimmen Sie in einem Programm für ein einzulesendes Jahr, ob es sich um ein Schaltjahr handelt.
2. Ergänzen Sie das Programm um die wiederholte Eingabe des Jahres, bis eine leere Zeichenkette eingegeben wird.
   Verwenden Sie dazu eine `do-while`-Schleife.


## 3. Datentypen, Ein- und Ausgabe

In einer Parallelwelt bietet eine Telefongesellschaft ihren Kunden den folgenden Mobilfunktarif:

*In der monatlichen Gebühr von 3,99 Euro sind 100 freie Minuten eingeschlossen, darüber hinaus kostet jede Minute 9,9 Cent.*

1. Erstellen Sie ein Programm, das die Monatsgebühr in Abhängigkeit von der Minutenzahl berechnet. Legen Sie die Minutenzahl zunächst testweise im Code fest.

2. Realisieren Sie eine dynamische Eingabe der Minutenzahl z. B. über die Kommandozeile.

3. Für das Datenvolumen stehen drei Tarifoptionen zur Auswahl, die ebenfalls monatlich abgerechnet werden:

    - **Tarif S**: 3 GB Datenvolumen für 5 Euro
    - **Tarif M**: 6 GB Datenvolumen für 7 Euro
    - **Tarif L**: 10 GB Datenvolumen für 10 Euro

    Lesen Sie zusätzlich zur Minutenzahl auch den gewählten Tarif ein (z.B. als `char`) und passen Sie die Berechnung der Monatsgebühr entsprechend an.


## 4. Random, Listen, Pandas

Es soll folgendes Spiel durch ein Programm simuliert werden:

Der Spieler zahlt für jedes Spiel einen Einsatz von 1 Euro.
Er darf einmal mit 3 Würfeln würfeln.
Je nach gewürfelter Punktzahl bekommt der Spieler einen Gewinn entsprechend der folgenden Tabelle ausgezahlt:

Punktzahl | Gewinn in EUR
---       | ---
3-15      | 0
16        | 5
17        | 10
18        | 100

Simulieren Sie 1000 Spiele mit zufälligen Würfen und geben Sie die zugehörige Gewinn- Und Verlustrechnung inkl. Bilanz aus.


## 5. Datentypen, Arithmetik

Berechnen Sie den Funktionswert der Funktion

<a href="https://www.codecogs.com/eqnedit.php?latex=\bg{white}f(x)&space;=&space;\frac{3x&space;-&space;6}{(x&space;&plus;&space;2)(x&space;-&space;1)^2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\bg{white}f(x)&space;=&space;\frac{3x&space;-&space;6}{(x&space;&plus;&space;2)(x&space;-&space;1)^2}" title="f(x) = \frac{3x - 6}{(x + 2)(x - 1)^2}" /></a>

im Intervall `[a, e]` mit der Schrittweite `s`.
Die Intervallgrenzen sowie die Schrittweite sind einzulesen, x- und y-Werte sind tabellarisch auszugeben.
Es soll möglich sein, reelle Zahlen als Schrittweite anzugeben.

*Hinweis: Beachten Sie die Polstellen der Funktion und die Besonderheiten des Vergleichs von `double`-Werten.*



<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({ tex2jax: {inlineMath: [['$', '$']]}, messageStyle: "none" });
</script>
