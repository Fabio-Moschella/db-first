# Struttura Tabella: Used cars

## Nome tabella: `Used cars`

| name                 | Type          | attribute                                  | index       |
| -------------------- | ------------- | ------------------------------------------ | ----------- |
| id                   | INT           | A.I.,NOT NULL                              | PRIMARY KEY |
| model                | VARCHAR(50)   | NOT NULL                                   | INDEX       |
| brand                | VARCHAR(50)   | NOT NULL                                   | INDEX       |
| power_supply         | VARCHAR(50)   | NOT NULL                                   | INDEX       |
| km                   | INT           | NOT NULL,DEFAULT(0)                        |             |
| year_of_registration | YEAR          | NOT NULL                                   | INDEX       |
| color                | VARCHAR(50)   | NULL                                       |             |
| condition            | ENUM          | NULL , DEFAULT ('old','as new','very bad') |             |
| license_plate        | VARCHAR(10)   | NULL                                       | UNIQUE      |
| purchase_price       | DECIMAL(10,2) | NOT NULL                                   |             |
| sale_price           | DECIMAL(10,2) | NOT NULL                                   |             |
| changing_of_the_car  | ENUM          | NULL, DEFAULT ('automatic','manual')       | INDEX       |
| engine_horsepower    | DECIMAL(10,2) | NOT NULL                                   |             |
| number of ports      | TINYINT       | NOT NULL                                   |             |
|                      |               |                                            |             |
|                      |               |                                            |             |
