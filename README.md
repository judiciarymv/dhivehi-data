# Dhivehi Data

## atolls.csv

| Column | Description |
| --- | --- |
| letter_dv | Atoll letter in Dhivehi |
| letter_en | Atoll letter in English |
| name_dv | Formal name of the atoll in Dhivehi |
| name_en | Formal name of the atoll in English |

## countries.csv

| Column | Description |
| --- | --- |
| name_dv | Name of the country in Dhivehi |
| name_en | Name of the country in English |
| country_code | ISO 3166-1 alpha-2 code |
| dial_code | Calling code |

## courts.csv

| Column | Description |
| --- | --- |
| name_dv | Name of the court in Dhivehi |
| name_en | Name of the court in English |
| org_code | Organisation code for this court (assigned by President's Office) |
| court_code | Court code (used in case numbering)* |

\* Older records for the following courts would use different codes, as detailed below:

- Civil Court used the code "MC" (from މަދަނީ ކޯޓު)
- Criminal Court used the code "JC" (from ޖިނާއީ ކޯޓު)
- Family Court used the code "AC" (from އާއިލާއާބެހޭ ކޯޓު)
- Juvenile Court used the code "KC" (from ކުޑަކުދިންނާބެހޭ ކޯޓު)

## islands.csv

| Column | Description |
| --- | --- |
| atoll | Atoll that this island belongs to<br>(Will be the same letters used in [atolls.csv](#atollscsv) `letter_en` column.) |
| name_dv | Name of the island in Dhivehi |
| name_en | Name of the island in English |
| island_code | Island code (used in [courts.csv](#courtscsv) `court_code` column) |
| feature_code | Unique feature code (assigned by [MLSA](https://onemap.mv)) |
| longitude | Longitude |
| latitude | Latitude |
