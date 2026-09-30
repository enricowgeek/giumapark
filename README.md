# GiumaPark — sito

Sito di **GIUMA PARK di Favaro Tamara** — playground al coperto, sale per i compleanni,
centri estivi e invernali, allestimenti di palloncini e noleggio gonfiabili.
Via Don Federico Tosatto 5, Mestre (VE).

- **Indirizzo definitivo:** https://giumapark.it (appena il dominio punta qui)
- **Indirizzo tecnico:** https://enricowgeek.github.io/giumapark/

## Com'è fatto

Un sito statico: nessun database, nessun programma da tenere acceso, nessun costo.
Tutto il contenuto sta in `index.html`; le immagini nelle cartelle `foto/`, `palloncini/` e
i caratteri tipografici in `font/`.

Pubblicato con GitHub Pages dal ramo `main`: ogni modifica messa qui va online da sola
in meno di un minuto.

## Privacy

Il sito non usa cookie e non chiama servizi esterni quando si apre: i caratteri sono ospitati
qui dentro e la mappa di Google si carica solo se il visitatore preme il pulsante.
L'informativa è in `privacy.html`.

## Modulo di contatto

Il modulo spedisce le richieste con **Web3Forms** (servizio gratuito): arrivano come email a
giumapark@gmail.com. La chiave del servizio sta in `index.html`, nel campo nascosto
`access_key` del modulo.

Se l'invio non riesce, nessuno resta senza un modo per scrivere: il sito prepara il messaggio
con quello che la persona ha compilato e lo fa arrivare a Tamara su WhatsApp, oppure via Gmail,
Outlook o il programma di posta del computer. C'è sempre anche il numero di telefono e
l'indirizzo email in chiaro.
