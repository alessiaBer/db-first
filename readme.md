**Descrizione:**
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

Entity: Pre-owned Car
Table name: Pre-owned Cars

COLUMNS

-id: PRIMARY_KEY, BIGINT, NOTNULL, AUTOINCREMENT

-brand: VARCHAR(30), NOTNULL

-model: VARCHAR(50), NOTNULL

-version: VARCHAR(50), NULL


-car_body: VARCHAR(50), NULL

-color: VARCHAR(50), NOTNULL

-seats: TINYINT, NOTNULL

-doors: TINYINT, NOTNULL



-price: DECIMAL(8, 2), NULL


-registration_date: DATE, NOTNULL

-registration_country: VARCHAR(50), NULL

-pre_owners: TINYINT, NULL


-mileage: MEDIUMINT, NOTNULL

-engine: VARCHAR(30), NOTNULL

-power_in_kw: SMALLINT, NOTNULL

-displacement: SMALLINT, NULL

-gear: VARCHAR(30), NULL

-wheel_drive: VARCHAR(30), NULL

-empty_weight: MEDIUMINT, NULL


-car_photo: VARCHAR(100), NULL

-description: TEXT, NULL



