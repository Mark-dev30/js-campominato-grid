CONSEGNA:

L'utente clicca su un bottone che genererà una griglia di gioco quadrata.
Ogni cella ha un numero progressivo, da 1 a 100. 
Ci saranno quindi 10 caselle per ognuna delle 10 righe. 
Quando l'utente clicca su ogni cella, la cella cliccata si colora di azzurro ed emetto
un messaggio in console con il numero della cella cliccata.


RISOLVO:
1 - L'utente clicca sul bottone che genera una griglia 10 x 10.
    1.1 - Creo un bottone con id "btn_play".
    1.2 - Creo una variabile "btn" a cui assegno il bottone appena creato.
    1.4 - Creo un funzione "createElement".
        1.4.1 - Creo un variabile "divElement" a cui assegno la creazione di un elemento div.
        1.4.2 - Aggiungo al div la classe "square".
        1.4.3 - Aggiungo il numero al div.
        1.4.4 - Ritorno la variabile "divElement".
    1.3 - Al click del pulsante
        1.3.1 - Creo una variabile "grid" a cui assegno l'id del contenitore "grid" creato in html.
        1.3.2 - Creo un ciclo for.
            1.3.2.1 - Passo come valori i=0, i<100, incremento i di 1.
2 - Assegno un numero ad ogni griglia.
    2.1 - All'interno del ciclo for.
        2.1.1 - Creo una variabile "currentSquare" a cui assegno la funzione "createElement" con valori i+1.
        2.1.2 - Inserisco all'interno di grid la variabile "currentSquare".
3 - Quando l'utente clicca su una cella, questa si colora di azzurro e mostra a schermo il numero della cella.
    3.1 - Aggiungo il click alla variabile "currentSquare".
    3.2 - Quando si clicca sopra la casella aggiungo una classe "click" e mostro a schermo il numero della casella.