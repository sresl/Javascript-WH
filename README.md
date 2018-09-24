# Javascript-WH

## Primitive Datentypen

#### Sechs Datentypen sind primitives:

##### Boolean / Null / Undefined / Number / String / Symbol / Object

Alle Datentypen, bis auf Object, definieren unveränderbare Werte (Werte, die nicht verändert werden können). Zum Beispiel im Gegensatz zu C sind Strings unveränderbar. Die Werte dieser Datentypen werden als "primitive Werte" bezeichnet.

Boolean repräsentiert eine logische Einheit und kann zwei Werte annehmen: true und false.

Der Null Typ hat genau einen Wert: null.

Eine Variable, der noch kein Wert zugewiesen wurde, hat den Wert undefined. 

Der Datentyp String wird in JavaScript für die Repräsentation von textuellen Daten verwendet. Er ist eine Menge von "Elementen" aus 16-Bit vorzeichenlosen Ganzzahlenwerten. Jedes Element im String nimmt eine eigene Position ein. Das erste Element befindet sich an der Position mit dem Index 0, das nächste beim Index 1 und so weiter. Die Länge eines String ist die Anzahl der sich darin befindenden Elemente.

In Gegensatz zu anderen Programmiersprachen wie C kann ein String in JavaScript nicht verändert werden. Das bedeutet, dass ein String nicht mehr verändert werden kann, nachdem er erstellt wurde. Es ist aber möglich einen anderen String mit der Hilfe von Operationen aus dem ursprünglichen String zu erstellen.

in Symbol ist ein eindeutiger und unveränderbarer primitiver Wert. Er kann als Schlüssel einer Eigenschaft eines Objekts verwendet werden. In manchen Programmiersprachen werden Symbole auch Atoms genannt.

In JavaScript können Objekte als eine Sammlung von Eigenschaften (Properties) angesehen werden. Mit der Object Literal Syntax werden die nötigsten Eigenschaften initialisiert. Danach können Eigenschaften hinzugefügt oder wieder entfernt werden. Der Wert einer Eigenschaft kann von jedem Datentyp sein. Darunter können sich auch andere Objekte befinden. Dadurch können komplexe Datenstrukturen realisiert werden. Eigenschaften werden mit einem Key identifiziert. Ein Key ist entweder ein String oder ein Symbol.

## Variablen

Variablen werden mit let oder var deklariert und sind ein Speicher oder Platzhalter für Daten wie Zahlen und Strings, deren Wert sich während der Ausführung des Scripts ändert.

## Operatoren

### Logische Operatoren

Mit den logischen Operatoren werden logische Verknüpfungen formuliert, z.B. für Abbruchbedingungen von Schleifen.

Mit dem logischen Operator && verknüpfen Sie zwei oder mehrere Bedingungen durch "und", d.h. beide bzw. alle Bedingungen müssen erfüllt sein, damit die gesamte Bedingung erfüllt ist.

Mit dem logischen Operator || verknüpfen Sie zwei oder mehrere Bedingungen inklusiv durch "oder", d.h. es genügt, wenn eine der Bedingungen erfüllt ist, damit die gesamte Bedingung erfüllt ist.

Der logische Operator ! (engl. not) prüft, ob ein Ausdruck unwahr ist. Der Ausdruck if (!name) trifft zu, wenn der Wert von name falsy ist, also ein Leerstring, null, undefiniert oder 0 ist.

### Vergleichsoperatoren

Vergleichsoperatoren dienen zum Vergleichen zweier Werte. Solche Vergleiche werden vor allem für bedingte Anweisungen und Schleifen benutzt.
Als Ergebnis liefern Vergleichsoperatoren immer entweder true (wahr) oder false (falsch).

### Zuweisungsoperatoren

Sie können zum Beispiel einer Variablen einen Wert zuweisen. Der Zuweisungsoperator dafür ist das Gleichheitszeichen. 

##### var SinnDesLebens = 42;
Mit dem Schlüsselwort var wird eine Variable namens SinnDesLebens definiert. Der Variablen wird mit dem Zuweisungsoperator = der Wert 42 zugewiesen.

### Rechenoperatoren

Numerische Berechnungen führen Sie mit Hilfe von Rechenoperatoren durch.

zum Addieren das Pluszeichen +
zum Subtrahieren das Minuszeichen -
zum Multiplizieren den Stern *
zum Dividieren den Schrägstrich /
für Modulo-Berechnungen das Prozentzeichen %

Es gelten die üblichen Rechenregeln (Punkt- vor Strichrechnung etc.). Wie in der Mathematik üblich, müssen Sie Klammern setzen, um eine andere Rangfolge der Operationen zu bestimmen.

var zwei           = 1 + 1,
    nix            = 2 - 2,
    auchNix        = 81 / 3 - 27,
    wenigerAlsNix  = 81 / (3 - 27),
    SinnDesLebens  = 6 * 7,
    ergibtAuchSinn = 84 / 2,
    wiederNix      = 36 * 37 % 666;

## Kommentar

Abschnitte im Quellcode, die als Kommentar gekennzeichnet sind, werden nicht als ausführbarer Code interpretiert.

Kommentare sind im einfachsten Fall ein Erklärungstext im Quellcode. Hierbei soll er den Leser dabei unterstützen, den Code zu verstehen.

#### Quellen:

https://wiki.selfhtml.org

https://www.mediaevent.de/javascript/variable.html

https://developer.mozilla.org/de/docs/Web/JavaScript/Datenstrukturen

## Ausgabe auf Bildschirm

## Verzweigungen

## Schleifen
