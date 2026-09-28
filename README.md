# SwapMarket
Piattaforma web per la compravendita e lo scambio diretto di libri scolastici usati tramite scansione ISBN.

Criteri:
1'cirterio=conoscenza/esperienza dell'utente
2'criterio=importanza

 User Story

 1. Come \[studente\], voglio \[scansionare il codice ISBN di un libro tramite la fotocamera\], così da \[trovare rapidamente le informazioni sul libro\].
2. Come \[studente\], voglio \[inserire manualmente il codice ISBN\], così da \[cercare un libro anche quando la fotocamera non è disponibile\].
3. Come \[studente\], voglio \[cercare libri per titolo, autore, ISBN o materia\], così da \[trovare facilmente il libro che sto cercando\].
4. Come \[studente\], voglio \[filtrare gli annunci per scuola, classe e anno scolastico\], così da \[visualizzare solo i libri adatti al mio percorso scolastico\].
5. Come \[studente\], voglio \[ordinare i risultati per prezzo, data di pubblicazione o distanza\], così da \[trovare più facilmente l'annuncio che mi interessa\].
6. Come \[venditore\], voglio \[pubblicare un annuncio per la vendita di un libro\], così da \[poterlo vendere ad altri utenti\].
7. Come \[venditore\], voglio \[pubblicare un annuncio per lo scambio di un libro\], così da \[poterlo scambiare con un altro libro\].
8. Come \[utente\], voglio \[pubblicare un annuncio per la donazione di un libro\], così da \[permettere a un altro utente di riceverlo gratuitamente\].
9. Come \[venditore\], voglio \[caricare fotografie del libro\], così da \[mostrare agli interessati le condizioni del libro\].
10. Come \[venditore\], voglio \[specificare le condizioni fisiche del libro\], così da \[informare correttamente i potenziali acquirenti\].
11. Come \[venditore\], voglio \[modificare o eliminare un annuncio\], così da \[mantenere aggiornati o rimuovere gli annunci non più validi\].
12. Come \[venditore\], voglio \[cambiare lo stato di un annuncio\], così da \[informare gli altri utenti sulla disponibilità del libro\].
13. Come \[studente\], voglio \[salvare libri e annunci nella Wishlist e tra i preferiti\], così da \[poterli ritrovare facilmente in seguito\].
14. Come \[studente\], voglio \[ricevere notifiche relative ai libri presenti nella mia Wishlist\], così da \[essere informato quando un libro che cerco diventa disponibile\].
15. Come \[acquirente\], voglio \[comunicare con il venditore tramite una chat privata\], così da \[potergli chiedere informazioni sul libro\].
16. Come \[acquirente\], voglio \[inviare offerte di prezzo e proposte di scambio\], così da \[poter negoziare con il venditore\].
17. Come \[acquirente\], voglio \[concordare un luogo e un orario per lo scambio\], così da \[poter effettuare lo scambio di persona\].
18. Come \[studente o genitore\], voglio \[creare un account\], così da \[poter utilizzare tutte le funzionalità dell'applicazione\].
19. Come \[utente registrato\], voglio \[effettuare il login e il logout\], così da \[accedere in modo sicuro al mio account e terminare la sessione\].
20. Come \[utente\], voglio \[modificare il mio profilo\], così da \[mantenere aggiornate le mie informazioni personali\].
21. Come \[utente\], voglio \[visualizzare lo storico degli annunci e delle transazioni\], così da \[tenere traccia delle mie attività\].
22. Come \[utente\], voglio \[segnalare annunci sospetti o inappropriati\], così da \[permettere al sistema di verificare e gestire gli annunci segnalati\].


Requisiti non funzionali

 1. Prestazioni: il sistema deve visualizzare i risultati di una ricerca entro 2 secondi.
2. Sicurezza: le password degli utenti devono essere memorizzate in modo sicuro.
3. Usabilità: l'interfaccia deve essere semplice e intuitiva anche per utenti inesperti.
4. Compatibilità: l'applicazione deve funzionare sui principali dispositivi Android e iOS.
5. Privacy: i dati personali degli utenti devono essere accessibili solo agli utenti autorizzati.
6. Disponibilità: il sistema deve essere disponibile almeno il 99% del tempo.

Requisiti di dominio

 1. Ogni libro di testo deve essere identificato tramite un codice ISBN.
2. Ogni libro deve essere associato a una materia, una classe e un anno scolastico.
3. Un annuncio deve essere classificato come vendita, scambio oppure donazione.
4. Un annuncio di vendita deve avere un prezzo maggiore o uguale a 0 €.
5. Un annuncio può avere esclusivamente gli stati disponibile, in trattativa o completato.
6. Un annuncio completato non può essere considerato disponibile per nuove trattative.

