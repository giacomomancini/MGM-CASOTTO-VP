# casotto-mgm

Progetto: Casotto
Meccanismo di decisione dei prezzi (fila, tipo di ombrellone,…), quindi meccanismi che definiscano politiche.
Servizio al bar per ombrelloni. Con l’app posso ordinare bibite da portare all’ombrellone, inquadrando il qr code sull’ombrellone.
Sistema di messaggistica associato alla app, tutti quelli che possono ricevere promozioni o da mandare a tutti quelli che hanno prenotato l’ombrellone.
Sistema di prenotazione per attività.

Applicazione web
Parte Server: Java (Springboot), DB relazionale
Parte front-end: altri strumenti
Framework grafico: JavaFx

02/11/2021

Attori
Cliente: chi prenota un ombrellone
Gestore
Organizzatore eventi
Ospite: chi partecipa ad eventi (esterno allo chalet)
Tempo

Casi d’uso
prenotazione ombrelloni/sdraio/lettini/cabina (intera/mezza giornata), pranzo/cena [attore: cliente];
prenotazione campi/attività ludico/sportive [attore: ospite];
gestione politiche, prezzi e promozioni [attore: gestore];
servizio bar, sistema di pagamento (diretto, indiretto, contanti) [attore: cliente];
organizzazione eventi ludico/sportivi, messaggi e notifiche [attore: organizzatore eventi];
modifiche, definizione caratteristiche chalet (struttura, impianti, campi) [attore: gestore];
jukebox [attore: ospite];
sistema di feedback e suggerimenti [cliente/ospite?]

Eventi
cliente: può prenotare anche per giorni diversi;
ospite: può prenotare solo per quel giorno


09/11/2021


Step 1: descrizione casi d’uso

Caso d’uso: 
ID:
Breve descrizione:


Attori primari:


Attori secondari:


Precondizioni:


Sequenza degli eventi principale:


Postcondizioni:


Sequenza degli eventi alternativa:




Step 2: creazione del diagramma delle classi di analisi (classi astratte, gestori che vengono fuori da processi)





3 schermi:
use case
modello di dominio
sequence diagram
