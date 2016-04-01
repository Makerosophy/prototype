Installazione
==========================

Di seguito le istruzioni per cominciare a lavorare.

(Istruzioni più dettagliate sul sito http://www.ryanbensonmedia.com/harvest.)

In questo momento è stato aggiunto il framework Bootstrap. Seguiranno Angularjs e un adattamento per lo stack MEAN.

Istruzioni
__________________________

* Effettua il download o clona questa repository
* Esegui il comando `npm install` per installare le dipendenze. Usa *sudo* se necessario.

Avrai bisogno di Gulp installato. Se è già installato salta la seguente riga:
* `npm install -g gulp`

Durante la modalità di sviluppo, utilizza le task di default per avere watchers e browser sync.
* Esegui `gulp` per iniziare
* Prova a modificare files html, css e javascript e a vedere come la pagina viene aggiornata con BrowserSync

Quando sei pronto al rilascio:
* Esegui `gulp deploy`
* Tutti i files di cui avrai bisogno saranno in /dist con immagini ottimizzate, css e js compressi
