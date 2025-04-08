## Nome della tabella: `Automobili`

## Colonne della tabella
`
- ID (BIGINT) - primary key - auto_increment - NOT NULL
- Marca (VARCHAR(20)) - NOT NULL
- Modello (VARCHAR(150)) - NOT NULL
- Colore (VARCHAR(50)) - NOT NULL
- Motore (VARCHAR(50)) - NOT NULL
- Cilindrata (INT) - NOT NULL
- Potenza CV (INT) - NOT NULL
- Cambio (VARCHAR(50)) - NOT NULL
- Emissioni CO2 (DECIMAL(6, 2)) - NOT NULL
- Carburante (VARCHAR(50)) - NOT NULL
- Chilometri (INT) - DEFAULT(0)
- Data immatricolazione (DATE) - NULL
- Stato (VARCHAR(50)) - NULL
- Accessori (TEXT) - NULL
- Prezzo (INT) - NOT NULL
- Disponibilità (TINYINT) - DEFAULT(1)
`