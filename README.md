# Ruby on Rails Tutorial: second application :)

This is the first application for
[*Ruby on Rails Tutorial: Learn Rails by Example*](http://railstutorial.org/)
by [Michael Hartl](http://michaelhartl.com/).

Lo scopo dell'applicazione è creare un'interfaccia web che permetta la registrazione di utenti
(di base) e l'inserimento di micro-post (Stile twitter).

Nonostante la navigazione non sia stata automatizzata, sono disponibili le pagine
--> users (che mostra tutti i clienti attualmente inseriti, con possibilità di inserirne di nuovi
   di modificare o eliminare contenuti).

--> microposts (che invece mostra i post dei singoli utenti, con le medesime funzionalità descritte sopra)

La struttura è stata realizzata mediante SCAFFOLD, non rappresenta quindi un esempio da scratch dello sviluppo 
di tali funzionalità. Il datamodel è costituito da sole due tabelle User e Micropost.
L'applicazione è stata deployata su Heroku.com