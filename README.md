# 21-12-13_Air-Quality-Regression

Ziel des Projekts ist ein Proof-of-Concept (PoC) für ein Machine Learning Model in der Cloud von Exone. 
Das Projekt soll bis 2022-06 fertig sein. Die Vorhersage der Luftqualität als Regression ist eines der PoCs.

## Der Datensatz
Der Datensatz stammt von aus dem [UCI ML repository](https://archive.ics.uci.edu/ml/datasets/air+quality).

| **Feature No.** | **Description**                                                                                          |
|-----------------|----------------------------------------------------------------------------------------------------------|
| 0               | Date (DD/MM/YYYY)                                                                                        |
| 1               | Time (HH.MM.SS)                                                                                          |
| 2               | True hourly averaged concentration CO in mg/m^3 (reference analyzer)                                     |
| 3               | PT08.S1 (tin oxide) hourly averaged sensor response (nominally CO   targeted)                            |
| 4               | True hourly averaged overall Non Metanic HydroCarbons concentration in   microg/m^3 (reference analyzer) |
| 5               | True hourly averaged Benzene concentration in microg/m^3 (reference   analyzer)                          |
| 6               | PT08.S2 (titania) hourly averaged sensor response (nominally NMHC   targeted)                            |
| 7               | True hourly averaged NOx concentration in ppb (reference analyzer)                                       |
| 8               | PT08.S3 (tungsten oxide) hourly averaged sensor response (nominally NOx   targeted)                      |
| 9               | True hourly averaged NO2 concentration in microg/m^3 (reference analyzer)                                |
| 10              | PT08.S4 (tungsten oxide) hourly averaged sensor response (nominally NO2   targeted)                      |
| 11              | PT08.S5 (indium oxide) hourly averaged sensor response (nominally O3   targeted)                         |
| 12              | Temperature in °C                                                                                       |
| 13              | Relative Humidity (%)                                                                                    |
| 14              | AH Absolute Humidity                                                                                     |

## Regressionsaufgabe
Vorhergesagt werden soll Feature 14, absolute Humidity. 
test
