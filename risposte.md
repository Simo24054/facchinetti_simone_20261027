1_ il DOM document object model è una struttura organizzata della pagina web sotto forma di albero rovescito dove si possono vedere i nodi padri e i nodi figli.

2_Quando un utente digita l'indirizzo del sito e preme invio, si attiva un processo sequenziale:
* Risoluzione DNS: Il client (il browser web) non conosce l'indirizzo IP del server. Interroga quindi il sistema DNS (Domain Name System), che traducendo l'URL testuale in un indirizzo IP numerico.
* Richiesta HTTP : Una volta ottenuto l'IP, il client stabilisce una connessione e invia una richiesta al server (il computer  che ospita il sito). In questa fase viene usato il metodo HTTP GET, che serve specificamente a richiedere una risorsa (la pagina HTML).
* Risposta HTTP : Il server elabora la richiesta, individua il file e lo spedisce indietro al client. La risposta include un codice di stato HTTP, come il codice 200 OK, che indica che la richiesta è andata a buon fine e la risorsa è disponibile.
* Rendering (Visualizzazione): Il browser riceve l'HTML, costruisce il DOM e infine visualizza la pagina all'utente.
