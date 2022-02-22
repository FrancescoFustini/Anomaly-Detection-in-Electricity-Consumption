<p align="center">
<img src="https://github.com/albi9702/Kobe-Vs-Machine-Learning/blob/master/Immagini/Logo-Bicocca.png"/>
</p>

# Anomaly Detection in Electricity Consumption

##### Progetto per l'esame di Streaming Data Science Lab del corso di laurea magistrale in Data Science all'università UniMiB

## Abstract 

Il progetto si propone di studiare alcuni metodi di *anomaly detection* applicati a serie storiche relative ai consumi di elettricità in edifici universitari. L’obiettivo principale è identificare ed eventualmente spiegare la presenza di giornate caratterizzate da consumi anomali, con il fine ultimo di proporre un’integrazione del processo negli stessi sistemi di monitoraggio energetico permettendo un’analisi real time.
Partendo dai dati messi a disposizione dall’Università di Milano-Bicocca, relativi agli edifici U1 e U6, lo studio approfondisce alcune tecniche di *anomaly detection*: una decomposizione stagionale delle serie temporali, lo studio dei residui di modelli TBATS e SARIMA, l’implementazione di un modello Isolation Forest e la clusterizzazione con algoritmo K-means.
I risultati ottenuti sono analizzati singolarmente per edificio, riscontrando la presenza di anomalie soprattutto nei periodi di festività e nei periodi di chiusura o in giornate in cui si può ipotizzare l'avviamento di attività di manutenzione. Per quanto concerne i giorni anomali caratterizzati da consumi molto più elevati di quanto ci si aspetterebbe, si individuano delle date che rientrano nelle sessioni d’esame (Giugno-Luglio per un edificio e Febbraio per l’altro). Alcune giornate, inoltre, risultano etichettate come outliers per entrambi gli edifici, ad esempio nel caso del 6 Agosto 2018, dei giorni prossimi al Natale 2018, del 19 Giugno 2019, del 9 e 10 Luglio 2019 e del 6 Aprile 2020.
L’intero studio è svolto utilizzando il programma *R* (versione 4.0.4).}

## File

- **import_dati.R:** lettura, parte di analisi preliminare e creazione dei file di partenza per l'anomaly detection
- **anomaly_detection_u1.R:** preprocessing e anomaly detection per serie storica U1
- **anomaly_detection_u6.R:** preprocessing e anomaly detection per serie storica U6

## Team

- Arianna Pera
- Laura Rapino
- Francesco Fustini <a href = "https://www.linkedin.com/in/francesco-fustini-3158b115a/"><img src="https://github.com/albi9702/Kobe-Vs-Machine-Learning/blob/master/Immagini/linkedin.png" width = "2%"></a><a href = "https://github.com/FrancescoFustini"><img src="https://github.com/albi9702/Kobe-Vs-Machine-Learning/blob/master/Immagini/github.png" width = "2%"></a>
