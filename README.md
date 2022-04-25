# Dhivehi Data

## atolls.csv

The file has 4 columns:

| letter_dv | letter_en | name_dv | name_en |
| --- | --- | --- | --- |
| Atoll letter in Dhivehi | Atoll letter in English | Formal name of the atoll in Dhivehi | Formal name of the atoll in English |

## countries.csv

The file has 4 columns:

| name_dv | name_en | country_code | dial_code |
| --- | --- | --- | --- |
| Name of the country in Dhivehi | Name of the country in English | ISO 3166-1 alpha-2 code | Calling code |

## courts.csv

The file has 4 columns:

| name_dv | name_en | org_code | court_code |
| --- | --- | --- | --- |
| Name of the court in Dhivehi | Name of the court in English | Organisation code for this court (assigned by President's Office) | Court code (used in case numbering)* |

\* Older records for Family Court would use the court code "AC" (from its older name އާއިލާއާބެހޭ ކޯޓު).

## islands.csv

The file has 4 columns:

| atoll | name_dv | name_en | island_code |
| --- | --- | --- | --- |
| Atoll that this island belongs to<br>(Will be the same letters used in **atolls.csv** `letter_en` column.) | Name of the island in Dhivehi | Name of the island in English | Island code |
