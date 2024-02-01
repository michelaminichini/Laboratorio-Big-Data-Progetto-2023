# Laboratorio-Big-Data-Progetto-2023
Progetto realizzato per il Laboratorio di Big Data, Data Mining e Data Analytics (2023/2024).

Per questo progetto, sono stati scelti due file csv che complessivamente raccolgono dati sulle 10 canzoni più popolari per ciascuno dei 10.000 artisti più ascoltati negli Stati Uniti.
Il set di dati copre una vasta gamma di generi musicali e copre un periodo di tempo specifico, catturando le preferenze dinamiche degli appassionati di musica nel Paese. Ogni voce include dettagli come il nome dell'artista, i titoli delle canzoni, le date di pubblicazione e le classifiche di popolarità basate su metriche come il numero di streaming o le posizioni in classifica. 

Inoltre, per comodità, è stato creato un terzo file chiamato 'Merged_dataset.csv' che contiene il merge, ossia l'unione, dei due file csv originari grazie all'ID dell'artista, essendo fattore comune tra i due file. Questo terzo file, al contrario del file chiamato 'top_songs', non presenta valori duplicati, perciò l'analisi dei dati risulta più precisa.

## Obiettivo del progetto
L'obiettivo principale è analizzare la dinamica temporale del successo musicale, concentrandosi su diversi fattori. Partendo da una ricerca generale, si è arrivati ad un'analisi più dettagliata per quanto riguarda un certo periodo di tempo, categorizzato in decenni. 
La ricerca include l'identificazione dei generi musicali e degli artisti più ascoltati nel tempo, l'analisi delle tendenze della popolarità delle canzoni nel corso degli anni, e la possibile individuazione di fattori significativi nell'analisi della correlazione. Lo studio infatti, come analisi finale, si concentra sullo scoprire la correlazione tra alcune variabili di interesse per poter osservare la loro relazione. Al posto di utilizzare dei grafici per questa ultima sezione, è stato sfruttato l'indice di correlazione, dunque il solo risultato matematico, per poter trarre delle conclusioni dai risultati.
Attraverso questa esplorazione, si mira ad ottenere una visione dei fattori chiave che influenzano il successo degli artisti e delle canzoni nel dataset.
Con l'intera ricerca, si vogliono conoscere le tendenze musicali nei vari decenni per poter osservare la presenza di convergenze o discrepanze, in modo da poter visualizzare come le varie preferenza musicali si sono evolute.

Nel progetto, a seguito delle operazioni effettuate, sono stati inseriti diversi grafici per poter visualizzare i risultati in modo più chiaro. Sono stati inoltre usati dei colori per poter categorizzare e comprendere maggiormente alcuni risultati ottenuti.

## Documentazione
- https://www.kaggle.com/datasets/ per la ricerca di un dataset 
- https://www.kaggle.com/datasets/spoorthiuk/us-top-10k-artists-and-their-popular-songs/?select=Top_Songs_US.csv il dataset scelto
- https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html#user-guide
- https://pandas.pydata.org/pandas-docs/stable/reference/index.html#api
- https://matplotlib.org/stable/api/index.html
