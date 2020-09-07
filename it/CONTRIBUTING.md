# Guida alla Contribuzione

- Contribuire a The Documentation Compendium è relativamente facile. Questo documento ti illustra come iniziare

## In Generale

- La [Struttura della Codebase](./CODEBASE_STRUCTURE.md) haa informazioni dettagliate su come i vari file in questo progetto sono strutturati
- Per favore assicurati che ogni modifica che fai sia in accordanza con le [Linee Guida di Programmazione](./CODING_GUIDELINES.md) di questa repository.

## Sottomettere Cambiamenti

- Forka la repo
  - <https://github.com/kylelobo/The-Documentation-Compendium/fork>
- Crea una nuova branch e dalle un nome inerente a quello che vuoi fare:
  - Esempio:
    ```
    $ git checkout -b NOME_BRANCH
    ```
    Se riscontri un errore, potresti aver bisogno di fetchare fooBar con
    ```
    $ git remote update && git fetch
    ```
  - Usa una branch per fix / feature
- Committa le tue modifiche
  - Per favore fornisci un messaggio git che spiega cosa hai fatto
  - Per favore assicurati che i tuoi commit seguano le [convenzioni](https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53#file-commit-message-guidelines-md)
  - Committa sulla repo forkata
  - Esempio:
    ```
    $ git commit -am 'Aggiunto fooBar'
    ```
- Pusha sulla branch
  - Esempio:
    ```
    $ git push origin NOME_BRANCH
    ```
- Fai una pull request
  - Assicurati di mandare la PR alla branch <code>fooBar</code>
  - Travis CI is watching you!

Se segui queste istruzioni, la tua PR arriverà tranquillamente nella repo principale!
