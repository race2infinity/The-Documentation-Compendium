Queste sono le cartelle che stiamo usando attivamente nello sviluppo:

- [frontend/server/controllers](https://github.com/kylelobo/The-Documentation-Compendium/tree/master/frontend/server/controllers): I controller che si occupano della logica ed espongono l'API del server.
- [frontend/server/libs](https://github.com/The-Documentation-Compendium/tree/master/frontend/server/libs): Librerie e servizi.
- [frontend/server/libs/dao](https://github.com/The-Documentation-Compendium/tree/master/frontend/server/libs/dao): Data Access Objects [DAO] e Value Objects [VO]. Classi usate per rappresentare schemi di database e facilitarne l'utilizzo per i controller.
- [frontend/templates](https://github.com/The-Documentation-Compendium/tree/master/frontend/templates): Template intelligenti usati per generare l'HTML che viene visualizzato dagli utenti.
- [frontend/www](https://github.com/The-Documentation-Compendium/tree/master/frontend/www): I contenuti completi della pagina Internet.

### frontend / www

Contenuto:

- js /
- css /

#### js

Come implica il nome, questa cartella è dove risiedono tutti i font javascript e i framework javascript. Quando vuoi apportare modifiche, per favore, minimizza il codice javascript e poi carica.

#### css

Analogo a js, contiene i file css minimizzati.

### frontend / server

Contenuto:

- dao /
- controllers /

Nessuno di questi moduli dovrebbe essere accessibile al mondo esterno. L'unico che può chiamarli è l'interfaccia utente. Questo è il motivo per cui sono dentro alla cartella www.

#### DAO / VO

La cartella _dao_ contiene le classi per il livello di accesso ai dati. Ha 2 cose da sapere: _data access objects_ e _value objects_. I _value objects_ (VO) sono niente più che classi mappate direttamente a ciascuna delle tabelle nel database. Perciò, esiste una classe lì dentro chiamata Users, siccome c'è una tabella con lo stesso nome. Questa classe ha i suoi setter e getter per ogni campo nel database. I _data access objects_ (dao) sono classi statiche per ogni tabella, e servono ad ottenere e rendere gli oggetti _vo_ persistenti.

[Qua ci sono più informazioni su questo modello](http://www.ibm.com/developerworks/java/library/j-dao/)

#### Controller

I controller sono dove le decisioni sono fatte. Il controller usa i dao's e vo's per fare decisioni, e mai chiamare il database direttamente. In questo modo, si evita di avere controller separati per ogni modulo del progetto.
