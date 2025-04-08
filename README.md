# Database intro
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Cosa consegnare:
come visto in classe fai un file readme.md
inserisci nome della tabella,
inserisci le colonne per definire il modello
assicurati di indicare la struttura dati da usare ed eventuali attributi per ciascuna colonna

## nome tabella: 'macchine'
## colonne tabella: 
- marca: VARCHAR(50) - NOT NULL
- modello: VARCHAR (150) - NOT NULL
- targa: VARCHAR(7) - NULL
- colore: VARCHAR(30) - NULL
- anno: YEAR() - NOT NULL
- prezzo: DECIMAL (7,2) - NOT NULL
- carburante: VARCHAR(30) - NULL
- chilometraggio: MEDIUMINT - NOT NULL
- numero porte: TINYINT - NULL
- posti: TINYINT - NULL 
- descrizione: TEXT() - NOT NULL

