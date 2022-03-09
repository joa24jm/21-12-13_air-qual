# 21-12-13_Air-Quality-Regression

The goal of the project is to go through the [CRISP-DM cycle](https://www.atr-software.de/leistungen/ki/) of a Machine Learning Project.
For this project in particular, that means:
- Analyse the dataset 
- Discover and present patterns that you find
- Train a regressor on humidity and minimize the mean squared error
- Use XAI tools to explain your classifier to stakeholders and debug it

## The datasets
The dataset is public from the [UCI ML repository](https://archive.ics.uci.edu/ml/datasets/air+quality).

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
| 12              | Temperature in °C                                                                                        |
| 13              | Relative Humidity (%)                                                                                    |
| 14              | AH Absolute Humidity                                                                                     |

Depending on the number of groups and the interest of the students, a second dataset of the [SOEP](https://www.diw.de/en/diw_01.c.678568.en/research_data_center_soep.html) might be introduced.

## Timeline
- Freitag, 2022-03-18    
  - Auftaktveranstaltung mit Vorstellung der neuen Projekte (und Bildung der Gruppen zur Bearbeitung)
- Freitag, 2022-04-01
  - Vorstellung der Planung des ersten Sprints: Analyse
- Freitag, 2022-04-22   
  - Vorstellung der Planung des zweiten Sprints und  Review+Retrospektive des ersten Sprints
- Freitag, 2022-05-13
  - Vorstellung der Planung des dritten Sprints und Review+Retrospektive des zweiten Sprints
- Freitag, 2022-06-03 
  - Vorstellung der Planung des letzten Sprints und Review+Retrospektive des dritten Sprints
- Freitag, 2022-07-01
  - Abschlusspräsentation (sofern möglich als Postersession / alternativ online: 10:30 - 12:00 Uhr)

## Acess via Google colab
The colab notebook is [here](https://colab.research.google.com/drive/12Tww4mLmj0uLmoB9PnHVsYxPP9ouQRhN?usp=sharing).

