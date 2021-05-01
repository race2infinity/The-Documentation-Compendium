# Sourcecoderichtlinien

- Sie können überprüfen, ob Ihr Code diesen Richtlinien entspricht, indem Sie 
`stuff/php-format.py validate` ausführen
- Tabulatoren, keine Leerzeichen
- Das Zeilenende sollte im Unix-Stil (`\n`) und nicht im Windows-Stil (`\r\n`) 
sein.
- Das Öffnen von Klammern erfolgt in derselben Zeile wie die letzte Anweisung
```
    if (condition) {
        stuff;
    }
```
- Ein Leerzeichen zwischen Schlüsselwörtern und Klammern für: `if`, `else`, 
`while`, `switch`, `catch`, `function`
- Funktionsaufrufe haben vor den Klammern kein Leerzeichen
- In den Klammern bleiben keine Leerzeichen
- Ein Leerzeichen nach jedem Komma, jedoch ohne Leerzeichen davor
- Alle binären Operatoren müssen ein Leerzeichen davor und danach haben
- Es sollte nicht mehr als eine aneinanderfolgende Leerzeile geben
- Es sollten keine leeren Kommentare vorhanden sein
- Sie sollten keine Blockkommentare `/* ... */` verwenden, sondern nur 
Zeilenkommentare `// ...`
- Änderungen der Funktionalität müssen gemeinsam mit ihren jeweiligen neuen / 
geänderten Tests hochgeladen werden
- Exceptions müssen verwendet werden, um fehlerhafte Zustände zu melden. Die 
Verwendung von Funktionen, die true / false zurückgeben, ist zulässig, wenn es 
sich um erwartete Werte handelt
- Verwenden Sie gegebenenfalls [RAII](http://en.wikipedia.org/wiki/Resource_Acquisition_Is_Initialization), insbesondere bei der Verwaltung von 
Ressourcen (Dateien usw.)