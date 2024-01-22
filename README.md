# Laboratorio-Big-Data-Progetto-2023
Progetto realizzato per il Laboratorio di Big Data, Data Mining e Data Analytics (2023/2024).

Per questo progetto, sono stati scelti due file csv che complessivamente raccolgono dati sulle 10 canzoni più popolari per ciascuno dei 10.000 artisti più ascoltati negli Stati Uniti.
Il set di dati copre una vasta gamma di generi musicali e copre un periodo di tempo specifico, catturando le preferenze dinamiche degli appassionati di musica nel Paese. Ogni voce include dettagli come il nome dell'artista, i titoli delle canzoni, le date di pubblicazione e le classifiche di popolarità basate su metriche come il numero di streaming o le posizioni in classifica. 

Inoltre, per comodità, è stato creato un terzo file chiamato 'Merged_dataset.csv' che contiene il merge, ossia l'unione, dei due file csv originari grazie all'ID dell'artista, essendo fattore comune tra i due file. Questo terzo file, al contrario del file chiamato 'top_songs', non presenta valori duplicati, perciò l'analisi dei dati risulta più precisa.

## Obiettivo del progetto
L'obiettivo principale è analizzare la dinamica temporale del successo musicale, concentrandosi su diversi fattori.
La ricerca include l'identificazione dei generi più e meno ascoltati nel tempo, l'analisi delle tendenze della popolarità delle canzoni nel corso degli anni, e la possibile individuazione di cambiamenti significativi nelle preferenze musicali. 
Attraverso questa esplorazione, si mira ad ottenere una visione dettagliata dei fattori chiave che influenzano il successo delle canzoni nel dataset nel corso del tempo.
Come analisi finale, abbiamo effettuato delle correlazioni tra alcuni fattori e la popolarità dell'artista, costituita dal numero di followers in alcuni casi e dal valore di popolarità stesso in altri.

Nel progetto, a seguito delle operazioni effettuate, sono stati inseriti diversi grafici per poter visualizzare i risultati in modo più chiaro. Sono stati inoltre usati dei colori per poter categorizzare e comprendere maggiormente alcuni risultati ottenuti.

## Proprietà/funzionalità utilizzate
- cat.codes (https://pandas.pydata.org/pandas-docs/stable/user_guide/categorical.html#categorical-data) = utilizzato per convertire dati categorici (categorical data) in codici numerici. I dati categorici rappresentano dati che possono assumere un numero limitato e fisso di valori. Nel nostro caso, nel file "Artists.csv" abbiamo la colonna "Country", che contiene stringhe per rappresentare i codici delle nazioni (e.g. "CA" per Canada). Dunque, convertire questo tipo di dati in codici numerici può essere utile per alcune operazioni come la correlazione. Nel progetto, è stato utilizzato in un calcolo della correlazione e ha permesso di riportare i codici della categoria (category codes) per ogni elemento. Inoltre, ha assegnato a ciascuna categoria nella colonna "Country" un numero unico (un identifier).


## Documentazione
- https://www.kaggle.com/datasets/ per la ricerca di un dataset 
- https://www.kaggle.com/datasets/spoorthiuk/us-top-10k-artists-and-their-popular-songs/?select=Top_Songs_US.csv il dataset scelto
- https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html#user-guide
- https://pandas.pydata.org/pandas-docs/stable/reference/index.html#api
- https://matplotlib.org/stable/api/index.html
