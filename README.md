# Mapování RORu

## Popis sloupců

Soubor `data/mapping-2026-09-30.csv` obsahuje pouze přírůstkovou dávku ke dni 30. 9. 2026 a skládá se z následujících sloupců (každý řádek představuje právě jednu organizaci):

| Název sloupce | Popis                                                                                                                                                                                     |
|:--------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`        | Oficiální název organizace                                                                                                                                                                |
| `ic_id`       | Osmiciferný řetězec IČO                                                                                                                                                                   |
| `ror_id`      | Trvalý odkaz na identifikátor v registru ROR                                                                                                                                              |
| `is_vavai`    | Indikátor; byl nastaven na hodnotu 1, pokud daná organizace v prostředí CEA subjekty v IS VaVaI obsahovala již vyplněný identifikátor ROR. V opačném případě byla hodnota nastavena na 0. |