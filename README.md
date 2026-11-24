# smart-offerte-elenco

Elenco dei prodotti che smartofferteitalia.it legge da solo ogni ora (pannello: Altre fonti → Elenco automatico).

`prodotti.csv`, separato da punto e virgola, con le colonne:

- `asin`: il codice del prodotto su Amazon.it
- `titolo`: nome del prodotto, scritto dalla redazione
- `categoria`: indirizzo della categoria sul sito (`tech`, `casa-cucina`, `fai-da-te`, `moda-scarpe`…); vuoto = la sceglie il sito
- `descrizione`: una frase scritta dalla redazione

Niente prezzi né immagini: li aggiunge il sito solo dal servizio ufficiale di Amazon per gli affiliati (Creators API).
I prodotti vengono scelti leggendo siti di notizie e di offerte, mai le pagine di Amazon.
Un prodotto che resta fuori dall'elenco per 3 giorni sparisce dal sito.
