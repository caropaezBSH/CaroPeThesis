# CaroPeThesis
This repository is for me to store everything related to my Bachelor's thesis and keep a journal of what I am doing

# Journal
- Notes from email:
  -  First steps can be: 
  - Take one or two datasets  and upload the data in a Jupyter Notebook. 
  - Do a first visualization looking at the time and the number of bicycles on a day / per hour.
  - Think of data model (table) to store the data from different cities. 
- Jupyter Notebook was installed
- Jupyter Notebook created
- Downloaded different data sets
- Checking df.info() for each data set

## Data Set Shapes - Preprocessing Stage
- Würzburg
- Munich
- Augsburg:
      <class 'pandas.core.frame.DataFrame'>
    MultiIndex: 2696 entries, ('Time', 'Dieselbrücke', 'Friedberger Straße östlich Afrabrücke', 'Friedrich-Ebert-Straße östlich Haltestelle Messe', 'Färberstraße/Gollwitzerstr.', 'Gögginger Straße südlich Rosenaustraße', 'Haunstetter Straße Höhe protestantischer Friedhof', 'Konrad Adenauer Allee Fahrradstraße', 'Postillionstraße südl. Roggenstraße', 'Rosenaustraße westlich Gögginger Straße', 'Südlich A8-Unterführung, Ostseite') to ('2024-02-01 00:00:00', nan, nan, nan, nan, nan, nan, '410', nan, nan, nan)    Data columns (total 3 columns):
     #   Column                                             Non-Null Count  Dtype  
    ---  ------                                             --------------  -----  
     0   Zeitraum                                           2330 non-null   object 
     1   16. September 2016 00:00 -> 1. Februar 2024 08:30  2253 non-null   object 
     2   Unnamed: 2                                         0 non-null      float64
    dtypes: float64(1), object(2)
    memory usage: 614.2+ KB

- Stuttgart
- Berlin
- Köln

|  **City** |  **Columns** | **Rows** | 
|:-----|-----:|---:|
| Würzburg  |  15 |   |
| Munich |   |   |
| Augsburg  |  13 |   |
| Berlin  |   |   |
| Münster  |   |   |
| Köln  |   |   |
