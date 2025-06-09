# Struttura Tabella: Used cars

## Nome tabella: `Used cars`

| name                 | Type                            | attribute     | index       |
| -------------------- | ------------------------------- | ------------- | ----------- |
| id                   | INT                             | A.I.,NOT NULL | PRIMARY KEY |
| model                | VARCHAR(50)                     | NOT NULL      | INDEX       |
| brand                | VARCHAR(50)                     | NOT NULL      | INDEX       |
| power supply         | VARCHAR(50)                     | NOT NULL      |             |
| KM                   | INT                             | NOT NULL      |             |
| Year of registration | YEAR                            | NOT NULL      | INDEX       |
| Color                | VARCHAR(50)                     | NULL          |             |
| conditions           | ENUM('old','as new','very bad') | NULL          |             |
| License plate        | VARCHAR(10)                     | NULL          |             |
| Purchase price       | INT                             | NOT NULL      |             |
| Sale price           | INT                             | NOT NULL      |             |
| Changing of the car  | ENUM('automatic','manual')      | NULL          | INDEX       |
|                      |                                 |               |             |
|                      |                                 |               |             |
|                      |                                 |               |             |
|                      |                                 |               |             |
