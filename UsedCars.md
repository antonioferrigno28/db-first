# Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

| name               | type         | attributes                         | key     | note                        |
| ------------------ | ------------ | ---------------------------------- | ------- | --------------------------- |
| id                 | BIGINT(20)   | NOT NULL - AUTOINCREMENT- UNSIGNED | PRIMARY |                             |
| brand              | VARCHAR(50)  | NOT NULL                           |         |                             |
| nome_modello       | VARCHAR(50)  | NOT NULL                           |         |                             |
| cilindrata         | SMALLINT     | NOT NULL - UNSIGNED                |         |                             |
| CV                 | SMALLINT     | NOT NULL - UNSIGNED                |         |                             |
| numero_porte       | TINYINT      | NOT NULL - UNSIGNED                |         |                             |
| numero_sedili      | TINYINT      | NOT NULL - UNSIGNED                |         |                             |
| condizioni         | TINYINT      | NOT NULL - UNSIGNED                |         | RATING DA 1 A 5             |
| classe_emissioni   | CHAR(6)      | NOT NULL                           |         |                             |
| anno               | YEAR         | NOT NULL                           |         |                             |
| prezzo             | DECIMAL(8,2) | NOT NULL - UNSIGNED                |         |                             |
| disponibilità      | TINYINT      | NOT NULL -DEFAULT(1)               |         | DISPONIBILITA' SI'(1)/NO(0) |
| kilometri_percorsi | MEDIUMINT    | NOT NULL - UNSIGNED                |         |                             |
