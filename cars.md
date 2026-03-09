| Nome colonna      | Tipo di dato | Attributi                     | Indice      |
| ----------------- | ------------ | ----------------------------- | ----------- |
| id                | BIGINT       | UNIQUE,NOTNULL,AUTO_INCREMENT | PRIMARY KEY |
| chassis number    | CHAR(17)     | UNIQUE,NOTNULL                | INDEX       |
| license plate     | CHAR(7)      | UNIQUE,NOTNULL                | INDEX       |
| marca             | VARCHAR(50)  | NOTNULL                       |             |
| model             | TEXT         | NULL                          |             |
| year registration | YEAR         | NULL                          |             |
| fuel type         | VARCHAR(50)  | NULL                          |             |
| gear              | VARCHAR(20)  | NULL                          |             |
| kilometers        | VARCHAR(20)  | NULL                          |             |
| price             | FLOAT(10,2)  | NOTNULL                       |             |
