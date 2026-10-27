nome : Simone Facchinetti 
classe : 5Bt-i

elenco pagine: 
index.html : Presentazione del cinema e tre film in programmazione
programmazione.html : Tabella degli orari della settimana
prenota.html : Modulo per prenotare i biglietti
contatti.html : Indirizzo, orari di apertura e come arrivare 

comandi usati :

$ cd C:/Users/Studente.PC11-LAB93A/Desktop/facchinetti_simone_20261027/esercizio1
(mi sposto nella directory)

Initialized empty Git repository in C:/Users/Studente.PC11-LAB93A/Desktop/facchinetti_simone_20261027/esercizio1/.git/


$ gh auth status
(verifico se eè connesso qualcun'altro )

$ gh auth login
(faccio il login su git hub)
$ git config user.name "simone facchinetti"


$ git config user.email "simofressa@gmail.com"


$ gh repo create facchinetti_simone_20261027 --public --source=. --remote=origin
(creo la repository su git hub)

$ git add index.html



$ git commit -m "creato il file index "

(faccio il commento del file )

$ git push

(invio il commento su git hub)

$ git push -u origin main

(pusho la root principale main )

