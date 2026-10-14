# __CSS-diner__

## Esercizio 1 -> plate oppure *
La manche richiedeva di selezionare tutti i 'plate':
* opzione selettore di elemento, selezionando l'elemento plate posso selezionare da 0 a N elementi e quindi eseguire la consegna.
* opzione selettore * in quanto chiedeva di selezionare tutti i piatti.
## Esercizio 2 -> bento
In questo esercizio ho usato il selettore di elemento (in questo caso 'bento') così che vengano selezionati tutti gli elementi bento.
## Esercizio 3 -> #fancy
In questo ho usato il selettore di id in quanto chiedeva di selezionare solo i piatti 'fancy' quindi vedendo il codice ho visto che solo un elemento aveva id=fancy e allora ho scritto nella regola css #fancy.
## Esercizio 4 -> plate apple oppure plate>apple
In questo esercizio chiedeva di selezionare la mela sul piatto:
* opzione 1 usare un selettore relazionale selezionando l'elemento plate e l'elemento apple così da andare a dire di selezionare solo gli elementi apple figli dell'elemento plate.
* opzione 2 usare un selettore di figlio diretto in quanto l'elemento apple è figlio diretto di plate.
## Esercizio 5 -> #fancy pickle
Qui ho usato di nuovo un selettore relazionale, sta volta la relazione è tra l'attributo #fancy (genitore) e l'elemento pickle (figlio) in quanto nella struttura HTML è al suo interno. 
## Esercizio 6 -> .small 
In questo caso ho usato un selettore di classe (.small) così da selezionare da 0 a N elementi con la classe di tipo small.
## Esercizio 7 -> orange.small
Qui ho usato orange.small dato che veniva richiesto di selezionare le oranges small, dalla struttura HTML risultava che i 2 elementi <oranges> hanno la classe class="small", quindi ho fatto in modo che venissero selzionati da 0 a N elementi con classe di tipo "small". 
## Esercizio 8 -> bento orange.small oppure bento>orange.small
In questo esercizio veniva chiesto di selezionare tutti gli elementi orange con classe small all'interno dell'elemento bento.  
* opzione a: selettore discendente -> bento orange.small  
    In questa opzione ho usato un selettore discendente ovvero lasciato lo spazio tra l'elemento genitore (bento) e l'elemento figlio (orange) con classe small.
* opzione b: selettore figlio diretto -> bento>orange.small  
    In questa opzione ho usato un selettore di figlio diretto collegando così l'elemento orange, che è in tutti e 2 i casi figlio diretto dell'elemento bento e ha classe small 
## Esercizio 9 -> bento, plate
In questo caso ho scritto "plate, bento" in quanto serviva selezionare tutti gli elementi plate e gli elementi bento presenti nella struttura HTML.
## Esercizio 10 -> *
In questo esercizio ho usato lo stesso selettore (*) usato nell'esercizio 1, anche in questo caso segnava di selezionare tutti gli elementi presenti nella pagina HTML.
## Esercizio 11 -> plate * oppure plate>*
* opzione 1: plate * in quanto con il selettore * seleziono da 0 a N elementi, creando la relazione con l'elemento plate seleziono da 0 a N elementi solo se figli dell'elemento N
* opzione 3: plate>* è uguale a plate * con l'aggiunta che gli elemento da 0 a N da selezionare devono essere figli diretti dell'elemento padre plate.
## Esercizio 12 -> plate+apple
Uso un selettore di figlio adiacente in quanto seguendo la struttura HTML e la consegna dell'esercizio devo prendere il primo elemento dopo l'elemento plate. Quindi usando questo selettore vado a prendere solo e soltanto il figlio adiacente (e quindi subito dopo).
## Esercizio 13 -> bento~pickle 
Ho usato questo selettore in quanto è il selettore di fratello generale e quindi seleziona tutti gli elementi fratelli che seguono l'elemento genitore (che devono obbligatoriamente avere in comune)
## Esercizio 14 -> plate>apple
In quanto dovevo selezionare l'elemento apple che era figlio diretto dell'elemento plate ho usato un selettore di figlio diretto, così che vengano presi solo 0-N elementi apple figli diretti dell'elemento plate nel documento HTML.
## Esercizio 15 -> orange:first-child
Dato che veniva richiesto di selezionare solo il primo elemento ho usato first-child.
## Esercizio 16 -> plate>apple, plate>pickle oppure plate>apple:only-child, plate>pickle:only-child
In questo caso ho trovato 2 opzioni:
* opzione 1: usare il selettore di figlio diretto in quanto guardando la struttura HTML gli elementi apple e pickle erano gli unici figli diretti dell'elemento plate. 
* opzione 2: ho aggiunto :only-child in quanto come detto prima era l'unico elemento figlio dell'elemento plate
## Esercizio 17 -> apple.small, pickle oppure apple.small:last-child, pickle:last-child
Usando le seguenti opzioni riesco a selezionare gli elementi apple con classe small e gli elementi pickle.
* opzione 1 -> apple.small, pickle con questo selettore di elementi e di classi riesco a selezionare gli elementi richiesti. 
* opzione 2 -> apple.small:last-child, pickle:last-child con questo selettore prendo l'elemento apple con classe di tipo small e tra gli 0-N elementi prendo solo l'ultimo figlio, stessa cosa vale con pickle (unica differenza non ha una classe).
## Esercizio 18 -> plate:nth-child(3) oppure plate:nth-last-child(2)
Con questi selettori analizzo gli 0-N elementi presenti nel file HTML:
* grazie a :nth-child(3) prendo solo il terzo elemento partendo a contare da sinistra.
* grazie plate:nth-last-child(2) prendo anche in questo caso solo il terzo elemento partendo però a contare da destra. 
## Esercizio 19 -> bento:first-of-type
In questo caso per selezionare il primo elemento bento ho usato :first-of-type in quanto seleziona il primo elemento dell'elemento selezionato.
Avessi usato :first-child avrei preso il primo elemento figlio dell'elemto genitore e quindi sarebbe stato l'elemento plate. 
## Esercizio 20 -> apple:first-of-type
Come per l'esercizio 19 anche in questo caso usando :first-of-type seleziono solo il primo tipo dell'elemento scelto.
## Esercizio 21 -> plate:nth-of-type(2n)
Grazie a :nth-of-type(2n) posso prendere gli elementi ogni 2, quindi partirà dal secondo elemento, salterà il terzo, prenderà il quarto e così via fino a quando gli elementi non saranno finiti.
## Esercizio 22 -> plate:nth-of-type(2n+3)
A differenza di prima adesso grazie alla formula (2n+3) prende non solo più gli elementi ogni due, ma inizia anche a selezionare gli elementi dal terzo elemento in poi.
## Esercizio 23 -> apple.small:only-of-type
Con questo selettore seleziono gli elementi apple con classe small, ma solamente se è l'unico elemento del suo tipo genitore.
## Esercizio 24 -> orange:last-of-type, apple:last-of-type
Con :last-of-type seleziono gli ultimi elementi di quello selezionato a cui la regola fa riferimento.
In questo caso seleziono l'ultimo elemento orange e l'ultimo elemento apple.
## Esercizio 25 -> bento:empty 
Grazie a :empty posso selezionare gli elementi (da 0 a N) vuoti.
## Esercizio 26 -> apple:not(.small)
Grazie all'aggiunta di :not posso selezionare tutti gli elementi tranne quello che segno all'interno delle parentesi.
In questo caso vengono selezionati tutti gli elementi apple tranne quelli con classe di tipo small.
## Esercizio 27 -> *[for]
Con questo selettore applico la regola CSS a tutti gli elementi che hanno un attributo di tipo for.
## Esercizio 28 -> plate[for]
In questo caso a differenza del selettore universale uso un selettore che limita solo determinati elementi (in questo caso plate) che devono avere però l'attributo for.
## Esercizio 29 -> bento[for="Vitaly"]
Anche qui uso il selettore di elemento con annesso l'attributo che in questo caso deve avere obbligatoriamente il valore "Vitaly".
## Esercizio 30 -> *[for^="Sa"]
Grazie a [for^="Sa"] seleziono tutti gli elementi presenti in pagina HTML con attributo for che inizia (^=) con Sa.
## Esercizio 31 -> *[for$="ato"]
In questo caso prendo gli elementi con l'attributo che finisce con 'ato', il tutto grazie al simbolo $ prima di =. 
## Esercizio 32 -> bento[for*="obb"]
In questo ultimo caso usando nell'attributo il simbolo * vado a selezionare gli 0-N elementi presenti in pagina ma solo se hanno un attributo for che contiene 'obb'.