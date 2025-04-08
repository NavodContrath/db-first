## Consegna
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle **auto usate** messe in vendita da un concessionario.

Cosa consegnare:
come visto in classe fai un file `readme.md`
inserisci nome della tabella,
inserisci le colonne per definire il modello
assicurati di indicare la struttura dati da usare ed eventuali attributi per ciascuna colonna
PUSHA

## Table name: `used_autos`

## Table columns:

- id (BIGINT) - primary key - auto_increment - NOTNULL
- chassis CHAR(17) - NOTNULL - UNIQUE
- brand VARCHAR(100) - NOTNULL
- model VARCHAR(100) - NOTNULL
- license_plate CHAR(7) - NOTNULL - UNIQUE
- year YEAR() - NOTNULL
- engine_capacity VARCHAR(10) - NOTNULL
- body_type VARCHAR(30) - NULL
- power VARCHAR(10) - NULL
- fuel VARCHAR(50) - NULL
- transmission A/M TINYINT - DEFAULT
- price FLOAT(10,3) - NOTNULL
- km MEDIUMINT - NULL
- condition VARCHAR(255) - NULL
- images VARCHAR(255) - NULL
- is_available TINYINT - DEFAULT(1)
- notes TEXT() - NULL