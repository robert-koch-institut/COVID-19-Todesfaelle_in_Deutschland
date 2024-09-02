### Variable specification for data file `frictionless_data_schema_COVID-19-Todesfaelle_Altersgruppen`

| Variable           | Typ     | Ausprägungen                                                     | Beschreibung                                                      |
|:-------------------|:--------|:-----------------------------------------------------------------|:------------------------------------------------------------------|
| Datum              | date    | Format: `%Y-W%U`                                                 | Kalenderwoche in der die Todesfälle an das RKI übermittelt worden |
| Altersgruppe       | string  | Werte: `00+`, `00-04`, `05-14`, `15-34`, `35-59`, `60-79`, `80+` | Altersgruppe der übermittelten COVID-19-Todesfälle in Jahren      |
| Todesfaelle        | integer | Minimum: 0                                                       | Anzahl der in der Kalenderwoche übermittelten Todesfälle          |
| Todesfaelle_gesamt | integer | Minimum: 0                                                       | Summe aller übermittelten Todesfälle                              |


### Variable specification for data file `frictionless_data_schema_COVID-19-Todesfaelle_Bundeslaender`

| Variable           | Typ     | Ausprägungen                                                                                                                                                                                                                                                  | Beschreibung                                                                                                                         |
|:-------------------|:--------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------|
| Datum              | date    | Format: `%Y-W%U`                                                                                                                                                                                                                                              | Kalenderwoche in der die Todesfälle an das RKI übermittelt worden                                                                    |
| Region_Name        | string  | Werte: `Baden-Württemberg`, `Bayern`, `Berlin`, `Brandenburg`, `Bremen`, `Hamburg`, `Hessen`, `Mecklenburg-Vorpommern`, `Niedersachsen`, `Nordrhein-Westfalen`, `Rheinland-Pfalz`, `Saarland`, `Sachsen`, `Sachsen-Anhalt`, `Schleswig-Holstein`, `Thüringen` | Name der Region der die übermittelten Fälle zugeordnet werden                                                                        |
| Region_Id          | string  | Werte: `01`, `02`, `03`, `04`, `05`, `06`, `07`, `08`, `09`, `10`, `11`, `12`, `13`, `14`, `15`, `16`                                                                                                                                                         | Identifikationsnummer der Region, basierend auf dem Amtlichen Gemeindeschlüssel (AGS), der die übermittelten Fälle zugeordnet werden |
| Todesfaelle        | integer | Minimum: 0                                                                                                                                                                                                                                                    | Anzahl der in der Kalenderwoche übermittelten Todesfälle                                                                             |
| Todesfaelle_gesamt | integer | Minimum: 0                                                                                                                                                                                                                                                    | Summe aller übermittelten Todesfälle                                                                                                 |


### Variable specification for data file `frictionless_data_schema_COVID-19-Todesfaelle_Deutschland`

| Variable                 | Typ     | Ausprägungen       | Beschreibung                                                         |
|:-------------------------|:--------|:-------------------|:---------------------------------------------------------------------|
| Berichtsdatum            | date    | Format: `%Y-%m-%d` | Datum, an dem die Todesfälle erstmals durch das RKI berichtet wurden |
| Faelle_gesamt            | integer | Minimum: 0         | Gesamtzahl aller übermittelten COVID-19-Fälle                        |
| Todesfaelle_gesamt       | integer | Minimum: 0         | Gesamtzahl aller übermittelten COVID-19-Todesfälle                   |
| Todesfaelle_neu          | integer | Minimum: 0         | Anzahl der am Berichtsdatum neu berichteten Todesfälle               |
| Fall-Verstorbenen-Anteil | number  | Minimum: 0         | Anteil der COVID-19-Todesfälle an allen COVID-19-Fällen              |


