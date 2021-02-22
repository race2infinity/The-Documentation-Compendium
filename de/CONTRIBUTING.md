# Leitfaden zur Mitwirkung

- An "The Documentation Compendium" mit zu wirken ist ziemlich einfach. Dieses 
Dokument zeigt die ersten Schritte

## Allgemeines
- Die [Codebase Structure](./CODEBASE_STRUCTURE.md) enthält detaillierte 
Informationen zur Struktur der verschiedenen Dateien in diesem Projekt
- Es muss sicher gestellt sein, dass alle vorgenommenen Änderungen den 
[Coding Guidelines](./CODING_GUIDELINES.md) dieses Repos entsprechen

## Änderungen einreichen

- Einen Fork des Repos erzeugen
  - <https://github.com/kylelobo/The-Documentation-Compendium/fork>
- Einen neuen Branch auschecken und einen Namen vergeben, der beschreibt, was 
geändert wird (z.B. <code>fooBar</code>): 
  - Beispiel:
    ````
    $ git checkout -b fooBar
    ````
    Falls ein Fehler ausgegeben wird, muss möglicherweise der aktuelle Stand 
    durch folgende Befehle geholt werden:
    ````
    $ git remote update && git fetch
    ````
  - Immer nur einen Branch pro Fix / Feature verwenden
- Änderungen übernehmen
  - Bitte eine Git-Nachricht verfassen, die beschreibt, was geändert wurde
  - Bitte sicherstellen, dass die Commits den [Konventionen](https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53#file-commit-message-guidelines-md) 
  entsprechen
  - Immer in das geforkte Repository commiten
  - Beispiel:
    ````
    $ git commit -am 'Add some fooBar'
    ````
- In den Branch pushen
  - Example:
    ````
    $ git push origin BRANCH_NAME
    ````
- Einen Pull-Request eröffnen
  - Sicherstellen, dass der PR an den Zweig <code>fooBar</code> gesendet wird
  - Travis CI is watching you!

Wenn diese Anweisungen befolgt werden, landet der PR ziemlich sicher im 
Haupt-Repo!