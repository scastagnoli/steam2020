# STEAM2020
Benvenuti nella pagina del corso STEAM "Tutti in forma con il coding :-)".

Il titolo "simpatico" sta ad indicare una specifica applicazione che ci siamo posti: realizzare un sistema elettronico, programmato da giovani, con cui poter interagire per una specifica ragione: essere guidati dal sistema in un sistema di allenamento.

Non ponendosi l'obiettivo di sostituire un personal trainer professionale questo progetto si propone di:
1. integrare strumenti tecnologici a basso costo con la vita di tutti i giorni
2. imparare ad applicare alcuni concetti base del coding specialmente tramite l'uso di tecnologie software basate sul linguaggio Scratch (https://scratch.mit.edu/)
3. apprezzare alcuni elementi di differenza fra un linguaggio "convenzionale" (Python/JavaScript/Visual Basic) e uno basata su logica "a blocchi"

Quello che ne è scaturito è un insieme di esercitazioni molto orientate alla pratica, senza molta teoria, allo scopo di realizzare subito "qualcosa" nel tentativo di superare le difficoltà iniziale nell'approccio a una nuova tecnologia in modo da stimolare la motivazione di chi non necessariamente è "nerd", cioè di chi non sia particolarmente interessato alla tecnologia in sè ma è interessato invece in alcune particolare applicazioni in cui la tecnologia ci può coinvolgere.

Il tutto è stato possibile grazie a:
* ISCOM Cesena
* ITC "R. Serra" di Cesena
* FabLab Romagna

## Esercizi

Di seguito si riporta una collezione di esercizi svolti dalle persone partecipanti. Sono stati raccolti solamente gli esercizi ritenuti più significativi per arrivare alle conoscenze che potessero permettere di risolvere l'esercizio finale.


[Esercizio 1](esercizi/esercizio1.md): contatore di numero testa e numero croce nel lancio di una moneta (https://makecode.microbit.org/_f8gCy5AaJMwt)

_Descrizione_: premendo il pulsante A viene simulato il lancio di un dado, premendo B vengono resettati i contatori del numero di teste e di croci

_Argomenti_: pressione pulsanti A e B, blocchi di logica (se/allora/altrimenti), mostra icona, controllo variabili, funzioni, concatenazione stringhe

[Esercizio 2](esercizi/esercizio2.md): contatore circolare modulo 10 (https://makecode.microbit.org/_0a1iqd2JcU5D)

_Descrizione_: premendo A ottengo la sequenza 1,2,3,…, 10,1,2,…; premendo B ottengo la sequenza 10,9,8,…1,10,9,8,… 

_Argomenti_: blocchi di logica (se/allora), controllo variabili, controllo pulsanti A e B, commenti al codice 

[Esercizio 3](esercizi/esercizio3.md): calcolatore di temperatura minima e massima (https://makecode.microbit.org/_f7C5E5XJXUKE)

_Descrizione_: premendo il pulsante A visualizzo la temperatura massima, premendo B la temperatura minima

_Argomenti_: variabili, sensore di temperatura, pressione pulsanti, blocchi di logica, visualizzazione dati su LED

[Esercizio 4](esercizi/esercizio4.md): temperatura media in un intervallo di tempo (https://makecode.microbit.org/_5pHR1qcHRK0w)

_Descrizione_: ogni 5 secondi visulizza la temperatura media fra quelle misurate ogni secondo

_Argomenti_: variabili, sensore di temperatura, blocchi logica (se/allora/altrimenti), operazione aritmetica (somma, divisione)

[Esercizio 5](esercizi/esercizio5.md): contapassi (https://makecode.microbit.org/_P6HhoXA4aFif)

_Descrizione_: utilizzando l'accelerometro integrato conto ogni passo che viene fatto. Un passo è contato quando l'accelerometro misura oscilla fra 1000mg e 0mg

_Argomenti_: variabili, porta seriale, accelerometro, funzione logica AND, blocchi logica

[Esercizio 6](esercizi/esercizio6.md): Prova di velocità pressione pulsante (https://makecode.microbit.org/_KKd2RzPK3EC1)

_Descrizione_: ogni 5 secondi viene visualizzato sulla porta seriale il numero di pressioni del pulsante A

_Argomenti_: variabili, scrittura su porta seriale, pausa, conversione numero in stringa


## Esercizio finale

[Link alla pagina del progetto](esercizi/esercizioFinale.md): programma di 3 tipi di allenamento differenziati per velocità espressa in passi/minuto (https://makecode.microbit.org/_2XtTbT8UTCeT)

A e B servono per attivare un tipo di allenamento
I LED visualizzano il tipo di allenamento: 1,2,3
A seconda del tipo di allenamento devo visualizzare un messaggio diverso a seconda del numero di passi al minuto:

	allenamento 1:
	
		numero passi al minuto < 30 => KO
		
		numero passi al minuto > 30 => OK
		
	allenamento 2:
	
		numero passi al minuto < 60 => KO
		
		numero passi al minuto > 60 => OK
		
	allenamento 3:
	
		numero passi al minuto < 90 => KO
		
		numero passi al minuto > 90 => OK
		
Il numero di passi al minuto deve essere calcolato sulla base di quanti passi vengono svolti in 5 secondi, quindi vengono moltiplicati per 12.



## Io c'ero!
Questa sezione è dedicata a un breve commento di alcuni partecipanti al corso: studentesse e studenti dell'ITC "R. Serra" di Cesena.


[Elenco dei partecipanti al corso](iocero.md)
