# Aprendendo-Mysql

## [CFB Cursos - My SQL](https://www.youtube.com/playlist?list=PLx4x_zx8csUgQUjExcssR3utb3JIX6Kra)

## Tipos

### Tipos numéricos

|        Tipo         |           0 até            |
| :-----------------: | :------------------------: |
|       TINYINT       |            255             |
|      SMALLINT       |           65.535           |
|      MEDIUMINT      |         16.777.215         |
|         INT         |       4.294.967.295        |
|       BIGINT        | 18.446.744.073.709.551.615 |
|  FLOAT(\<p>, \<e>)  |                            |
| DOUBLE(\<p>, \<e>)  |                            |
| DECIMAL(\<p>, \<e>) |                            |

p = precisão (quantidade de numeros)
e = escala(numero de casas decimais)

FLOAT(6, 2) = tamanho 6 com duas casas decimais: 1234,56

---

### Tipos de texto

|      Tipo       |  Bytes (max)  |
| :-------------: | :-----------: |
|    TINYTEXT     |      255      |
|  CHAR(\<qnt>)   |      255      |
| VARCHAR(\<qnt>) |    65.535     |
|      TEXT       |     65.5      |
|   MEDIUMTEXT    |  16.777.215   |
|    LONGTEXT     | 4.294.967.295 |

qnt = quantidade de caractes
1 Byte = 8 bits = 1 caractere

##### Char vs VarChar

Char tem um numero fixo independente do valor armazenado dentro dele

VarChar tem um valor limite seu tamanho varia de acordo com o valor armazenado dentro dele

---

### Tipos de data

|   Tipo    |       Formato       |
| :-------: | :-----------------: |
| DATETIME  | AAAA-MM-DD HH:MM:SS |
| TIMESTAMP | AAAA-MM-DD HH:MM:SS |
|   DATE    |     AAAA-MM-DD      |
|   TIME    |      HH:MM:SS       |
|   YEAR    |        AAAA         |

##### TimeStamp VS DateTime

Timestamp possue apenas 4 bytes com limite de data:
1970-01-01 00:00:01 UTC to 2038-01-09 03:14:07 UTC
e trabalha com timezone

Datetime possue 8 bytes com limite de data:
1000-01-01 00:00:00 to 9999-12-31 23:59:59
e não trabalha com timezone
