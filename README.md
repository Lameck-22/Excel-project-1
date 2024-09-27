### Cleaning
1. Removed duplicates
2. Changing marital status from (S->Single, M->Married) and Gender(M->Male, F->Female)
    - Click on the column
    - Ctrl + H
  
3. Changed income column from general to currency to be easily manipulated.
4. Created a new column for "Age-groups" using:
   =IF(L2>54,"Old",IF(L2>=31,"Middle age",IF(L2<31,"Adolescent","Invalid")))

### Visualizations
- Used pivot tables (An interactive way to quickly summarize large amounts of data)
- Then clicked on a cell with the data an derived a chart which best fits the data.

### Dashboard
- Created a new sheet and copyied the graphs generated there
- On the graphs, click
- Go to pivort chart analyze
- Insert Slicer

- Then you can click the slicer and go to report connection - to connect with the other copyied charts.
