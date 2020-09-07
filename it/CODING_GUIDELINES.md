# Linee Guida di Programmazione

- Puoi validare che il tuo codice segua queste linee guida eseguendo `stuff/php-format.py validate`
- Tab, non spazi
- Il fine riga dovrebbe essere stile Unix (`\n`), non stile Windows (`\r\n`)
- Le parentesi aperte vanno sulla stessa riga dell'ultima istruzione

```
    if (condition) {
        stuff;
    }
```

- Uno spazio tra parole chiave e parentesi per: `if`, `else`, `while`, `switch`, `catch`, `function`
- Chiamate di funzioni non hanno uno spazio prima delle parentesi
- Non ci sono spazi sulla sinistra dentro alle parentesi
- Uno spazio dopo ogni virgola, ma senza spazio prima
- Tutti gli operatori binari devono avere uno spazio prima e uno dopo
- Non dovrebbero esserci più di una linea vuota contigua
- Non dovrebbero esserci commenti vuoti
- Non dovresti usare commenti di blocco `/ * ... * /`, solo di linea `// ...`
- Modifiche alla funzionalità devono essere accompagnate da rispettivi test nuovi o modificati
- Eccezioni vanno usate per segnalare stati erronei. L'uso di funzioni che ritornano true / false è permesso quando sono i valori aspettati
- Usa [RAII] (http://en.wikipedia.org/wiki/Resource_Acquisition_Is_Initialization) quando adeguato, principalmente nell'amministrazione di risorse (file, etc ...)
