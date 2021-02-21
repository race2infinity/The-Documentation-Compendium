Dies sind die Verzeichnisse, die wir aktiv in der Entwicklung einsetzen:

+ [frontend/server/controllers](https://github.com/kylelobo/The-Documentation-Compendium/tree/master/frontend/server/controllers): 
Die Controller führen die Businesslogik aus und machen die Server-API verfügbar.
+ [frontend/server/libs](https://github.com/The-Documentation-Compendium/tree/master/frontend/server/libs): Bibliotheken und Dienstprogramme.
+ [frontend/server/libs/dao](https://github.com/The-Documentation-Compendium/tree/master/frontend/server/libs/dao): Data 
Access Objects [DAO] und Value Objects [VO]. Klassen, die zur Darstellung von 
Datenbankschemata und zur erleichterten Verwendung durch die Controller 
verwendet werden.
+ [frontend/templates](https://github.com/The-Documentation-Compendium/tree/master/frontend/templates): Smarty-Vorlagen zum Generieren des HTML-Codes, der den Benutzern angezeigt 
wird.
+ [frontend/www](https://github.com/The-Documentation-Compendium/tree/master/frontend/www): 
Der vollständige Inhalt der Internetseite.

### frontend / www
Inhalt:

+ js /
+ css /

#### js
Wie der Name schon sagt, befinden sich hier alle Javascript-Schriftarten und 
Javascript-Frameworks. Codeänderungen, die hier vorgenommen werden, müssen vor 
dem Upload mittels Minify komprimiert werden.

#### css
Ähnlich wie bei js sind hier die durch Minify verkleinerten CSS-Dateien.

### frontend / server
Inhalt:

* dao /
* controllers /

Keines dieser Module sollte für die Außenwelt zugänglich sein. Sie können 
lediglich durch die Benutzeroberfläche aufgerufen werden. Aus diesem Grund 
befinden sie sich im Ordner www.

#### DAO / VO

Der Ordner *dao* enthält die Klassen für die Datenzugriffsschicht. Hier gibt es 
zwei relevante Dinge: *data access objects* und *value objects*. 
*Value objects* (VO) sind nichts anderes als Klassen, die direkt jeder der 
Tabellen in der Datenbank zugeordnet sind. Daher gibt es dort beispielse eine 
Klasse namens Users, da es eine Tabelle mit dem selben Namen gibt. Diese Klasse 
hat ihre Setter und Getter für jedes der Felder in der Datenbank. Die 
*data access objects* (dao) sind statische Klassen für jede der Tabellen und 
dienen dazu, die Objekte zu erhalten und zu dauerhaften *VO*'s zu machen.

[Hier finden Sie weitere Informationen zu diesem Modell](http://www.ibm.com/developerworks/java/library/j-dao/)

#### Controller

In den Controllern werden die Entscheidungen getroffen. Der Controller verwendet 
die DAOs und VOs, um Entscheidungen zu treffen, und ruft die Datenbank niemals 
direkt auf. Auf diese Weise vermeiden wir separate Controller für jedes Modul 
des Projekts.

