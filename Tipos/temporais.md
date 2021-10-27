# Tipos de data

|   Tipo    |       Formato       |
| :-------: | :-----------------: |
| DATETIME  | AAAA-MM-DD HH:MM:SS |
| TIMESTAMP | AAAA-MM-DD HH:MM:SS |
|   DATE    |     AAAA-MM-DD      |
|   TIME    |      HH:MM:SS       |
|   YEAR    |        AAAA         |

## TIMESTAMP VS DATETIME

Timestamp possue apenas 4 bytes com limite de data:
1970-01-01 00:00:01 UTC to 2038-01-09 03:14:07 UTC
e trabalha com timezone

Datetime possue 8 bytes com limite de data:
1000-01-01 00:00:00 to 9999-12-31 23:59:59
e não trabalha com timezone
