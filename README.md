# Progetto_PMO_2024_2025_PiovaticciLuca

Escape Choice - Gioco interattivo di sopravvivenza e fuga

L'obiettivo del progetto è la realizzazione di un'applicazione che simuli un videogioco narrativo interattivo a scelta multipla, con meccaniche di sopravvivenza basate su vite, inventario, nemici, infezione ed eventi condizionati dalle scelte del giocatore.

Il contesto del gioco è composto da:
• Un giocatore, che all'avvio della partita ha la possibilità di inserire il proprio nome e selezionare un livello di difficoltà. Durante la partita puo raccogliere oggetti, perdere vite e affrontare situazioni di pericolo.
• Un insieme di stanze all'interno dell'ambiente, che rappresentano le scene della storia.
• Un gruppo di scelte possibili all'interno di ogni stanza, che permettono di decidere come proseguire la narrazione.
• Un inventario posseduto dal giocatore, che può contenere diversi oggetti (arma, codice, kit medico).
• Un meccanismo di infezione che può attivarsi sulla base di determinate scelte. 

Il gioco prevede che il giocatore abbia la possibilità di selezionare una tra le scelte possibili in ogni scena: ogni decisione porta a conseguenze diverse, come lo spostamento in un'altra stanza, l'acquisizione di oggetti, l'incontro con nemici o l'attivazione di condizioni di rischio. Sequenze diverse di scelte fatte possono portare alla vittoria della partita o alla sconfitta.

Requisiti minimi
• Scelte multiple testuali ad ogni scena, in alcuni casi la possibilità di tornare indietro, con percorsi ramificati.
• Gestione delle vite: al loro esaurimento la partita termina con la sconfitta.
• Gestione dell'inventario: contiene gli oggetti raccolti nel corso della partita.
• Gestione dei nemici con logica di combattimento semplificata. L'esito dei combattimenti è determinato dalla presenza di arma e vite.
• Presenza di finali multipli: percorsi diversi possono portare alla vittoria o alla sconfitta.
• Game over per esaurimento vite, mancanza di arma in inventario o scelte errate.
• Presenza di una GUI per l'interazione con l'utente: pulsanti per le scelte e testi narrativi delle scene.
• Salvataggio e caricamento della partita: persistenza degli stati tramite serializzazione.

Requisiti opzionali
• Scelta tra tre possibili livelli di difficoltà (easy, medium, hard), in base alla quale vengono impostate le vite iniziali.
• Visualizzazione di una mappa tramite una scelta specifica nel gioco.
• Inventario e numero di vite (dinamici) visibili durante la partita.
• Gestione del rischio in alcune scene del gioco (gestite random).
• Scrittura e lettura della narrazione delle scene da file esterno in formato JSON. Questo permette: una separazione tra logica e contenuti, facilità di aggiornamento della storia e possibilità di inserirne di nuove, estendibilità del gioco con storie diverse.

