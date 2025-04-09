# Database intro
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Cosa consegnare:
come visto in classe fai un file readme.md
inserisci nome della tabella,
inserisci le colonne per definire il modello
assicurati di indicare la struttura dati da usare ed eventuali attributi per ciascuna colonna

## nome tabella: 'cars'
## colonne tabella: 
- id: BIGINT - primary key- auto increment - NOTNULL
- brand: VARCHAR(50) - NOTNULL
- model: VARCHAR (150) - NOTNULL
- License_plate: CHAR(7) - NULL
- color: VARCHAR(30) - NULL
- year: YEAR() - NOTNULL
- price: DECIMAL (7,2) - NOTNULL
- Fuel: VARCHAR(30) - NOTNULL
- km: MEDIUMINT - NOTNULL
- number_doors: TINYINT - NULL
- seats: TINYINT - NULL 
- description: TEXT() - NOTNULL

