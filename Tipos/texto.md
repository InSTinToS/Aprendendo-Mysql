# Tipos de texto

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

## Char vs VarChar

Char tem um numero fixo independente do valor armazenado dentro dele

VarChar tem um valor limite seu tamanho varia de acordo com o valor armazenado dentro dele
