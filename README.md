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
- ### Würzburg:
  - RangeIndex: 231349 entries, 0 to 231348
  - Total Columns: 15
  -    Column             Non-Null Count   Dtype  
  - 0   Id                 231349 non-null  int64
  - 1   Date               231349 non-null  object
  - 2   Counts             153916 non-null  float64
  - 3   Status             153916 non-null  object
  - 4   Name               217150 non-null  object
  - 5   Coordinates        217150 non-null  object
  - 6   User Type          217150 non-null  object
  - 7   TimeZone           217150 non-null  object
  - 8   Interval           217150 non-null  float64
  - 9   Sens               217150 non-null  object
  - 10  Installation Date  217150 non-null  object
  - 11  Counter            108553 non-null  object
  - 12  Photos             108553 non-null  object
  - 13  photourl           108553 non-null  object
  - 14  photo              108553 non-null  object 

- ### Munich
- ### Augsburg:
  - MultiIndex: 2696 entries, ('Time', 'Dieselbrücke', 'Friedberger Straße östlich Afrabrücke', 'Friedrich-Ebert-Straße östlich Haltestelle Messe', 'Färberstraße/Gollwitzerstr.', 'Gögginger Straße südlich Rosenaustraße', 'Haunstetter Straße Höhe protestantischer Friedhof', 'Konrad Adenauer Allee Fahrradstraße', 'Postillionstraße südl. Roggenstraße', 'Rosenaustraße westlich Gögginger Straße', 'Südlich A8-Unterführung, Ostseite') 
        Column                                             Non-Null Count  Dtype  
     0   Zeitraum                                           2330 non-null   object 
     1   16. September 2016 00:00 -> 1. Februar 2024 08:30  2253 non-null   object 

- ### Stuttgart
- ### Berlin
- ### Köln

|  **City** |  **Columns** | **Rows** | 
|:-----|-----:|---:|
| Würzburg  |  15 |   |
| Munich |   |   |
| Augsburg  |  13 |   |
| Berlin  |   |   |
| Münster  |   |   |
| Köln  |   |   |
