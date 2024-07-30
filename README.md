### Text markieren

<kbd>Alt + J</kbd> -> Nächste Instanz des Markierten Textes mit Markieren <br>
<kbd>Alt + Shift + J</kbd> -> Momentane Instanz nicht mehr Markieren (Geht eigentlich nur nach Alt + J und ist Quasi in Ctrl + Z)<br>
Alt + Shift + Ctrl + J -> Alle Instanzen des Markierten Textes im momentanen File Markieren<br>

Strg + W -> Einen Scope weiter Markieren (Wenn der Cursor in einem Wort ist, wird das Wort markiert, nochmal drücken, dann wird das nächste umgebende Wort markiert etc. Wenn man unendlich oft drückt, markiert man irgendwann das gesamte File)<br>
Strg + Shift + W -> Einen Scope kleiner markieren (Quasi das Ctrl + Z für Ctrl + W)<br>

Strg + Shift + Alt -> Gedrückt halten und mit doppelclick mehrere "Wörter" markieren. Besonders toll, wenn man schnell mehrere Wörter bzw. Variablen ersetzen möchte und gerade nicht Alt + J benutzen kann / will<br>

### Refactoring

Shift + F6 -> Variable umbenennen<br>
Ctrl + Shift + P -> Variable als Parameter in der umgebenden Funktion oder Methode verwenden<br>
Ctrl + Shift + F -> Variable als Feld in der umgebenden Klasse benutzen<br>
Ctrl + Shift + C -> Ausdruck als Konstante speichern<br>
Ctrl + Shift + V -> Ausdruck in einer Variable speichern<br>
Ctrl + Shift + M -> Ausdruck in eine Funktion auslagern<br>


### Debugging

Alt + F8 -> Öffnet ein dediziertes Fenster in dem Code ausgeführt und der Rückgabewert analysiert werden kann

### This and That

Nach einem Statement oder einer Variable eingeben, dann Tab drücken um den "Vorschlag" anzunehmen: 
- .not -> negiert den begriff den man suffixt
- .arg -> umschließt den begriff mit "()" Klammern und der Cursor wird vor die Klammern gesetzt
- .return -> schreibt ein return vor den begriff
- .if -> umschließt den Begriff mit Klammern und schreibt ein if vor die Klammer und setzt automatisch "{}" Klammern
- .opt -> Umschließt den Begriff mit Optional.ofNullable()
- .log -> Umschließt den Begriff mit console.log()
