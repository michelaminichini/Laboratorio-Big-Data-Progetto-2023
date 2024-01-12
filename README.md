# Laboratorio-Big-Data-Progetto-2023
Realizzazione progetto per il Laboratorio di Big Data, Data Mining e Data Analytics (2023/2024)

Per questo progetto, sono stati scelti due file csv che complessivamente raccolgono dati sulle 10 canzoni più popolari per ciascuno dei 10.000 artisti più ascoltati negli Stati Uniti.
Il set di dati copre una vasta gamma di generi musicali e copre un periodo di tempo specifico, catturando le preferenze dinamiche degli appassionati di musica nel Paese. Ogni voce include dettagli come il nome dell'artista, i titoli delle canzoni, le date di pubblicazione e le classifiche di popolarità basate su metriche come il numero di streaming o le posizioni in classifica. 

## Documentazione
- https://www.kaggle.com/datasets/ per la ricerca di un dataset 
- https://www.kaggle.com/datasets/spoorthiuk/us-top-10k-artists-and-their-popular-songs/?select=Top_Songs_US.csv il dataset scelto

## Proprietà/funzionalità utilizzate
- cat.codes = utilizzato per convertire dati categorici (categorical data) in codici numerici. I dati categorici rappresentano dati che possono assumere un numero limitato e fisso di valori. Nel nostro caso, nel file "Artists.csv" abbiamo la colonna "Country", che contiene stringhe per rappresentare i codici delle nazioni (e.g. "CA" per Canada). Dunque, convertire questo tipo di dati in codici numerici può essere utile per alcune operazioni come la correlazione. Nel progetto, è stato utilizzato in un calcolo della correlazione e ha permesso di riportare i codici della categoria (category codes) per ogni elemento. Inoltre, ha assegnato a ciascuna categoria nella colonna "Country" un numero unico.

## Operazioni eseguite per analizzare il dataset
- il genere più ascoltato
- la canzone con più popolarità
- la canzone con meno popolarità
- l'artista più famoso. C'è una maggioranza per quanto riguarda il gender degli artisti tra quelli più famosi?
- analisi del genere degli artisti con gender maschile. Quali sono i generi più ascoltati?
- analisi delle canzoni esplicite e non. Quale categoria è più ascoltata?
- 3 esempi di correlazione: correlazione tra età dell'artista e numero di followers, correlazione tra nazione di provenienza e numero di followers e correlazione tra genere musicale e numero di followers.
- analisi di un determinato periodo in cui sono state rilasciate più canzoni. Anno - mese. Utilizzo di un grafico a barre per lettura dati
