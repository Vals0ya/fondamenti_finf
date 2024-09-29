Questo progetto fornisce un insieme di funzioni per elaborare e analizzare un file CSV chiamato heart1.csv, contenente dati relativi a pazienti. Le funzioni consentono di caricare, filtrare e analizzare i dati per ottenere informazioni significative sui pazienti e le loro caratteristiche.
get_unique_numbers(name): Restituisce i valori unici dalla colonna specificata.

carica_dati(): Carica i dati dal CSV in una lista di dizionari, con ogni riga rappresentata come un dizionario.

get_x_by_y(x, y, z): Estrae i valori dalla colonna x per le righe in cui la colonna y è uguale a z.

media(name): Calcola la media dei valori in una colonna specificata, gestendo errori di conversione.

get_values(name): Estrae tutti i valori dalla colonna specificata.

fornisco poi funzioni per generare istogrammi e grafici a torta utilizzando i dati da un file CSV:

get_hist(name): Restituisce due liste:
list4: contiene i valori unici della colonna specificata.
list3: conta quante volte ogni valore unico appare nella colonna, restituendo una lista di conteggi.
pie(name): Crea un grafico a torta per visualizzare la distribuzione dei valori unici nella colonna specificata. Utilizza le liste generate da get_hist per etichettare il grafico.
instx(): Genera un grafico a barre per confrontare il numero di intervistati in base a diverse categorie relative all'Indice di Massa Corporea (BMI), come fumo, sesso, razza e attività fisica. Ogni categoria è rappresentata sull'asse x, mentre il numero di intervistati è sull'asse y.

Qui il codice ci permette di analizzare e visualizzare graficamente i dati relativi al BMI e ad altre variabili nel dataset, facilitando l'interpretazione delle informazioni.






