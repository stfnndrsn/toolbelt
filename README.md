# toolbelt
Small tools and script to remember - here be dragons

## MySQL
### Import data from a /standard/ csv file into a table
```
LOAD DATA LOCAL INFILE "infile.csv"
INTO TABLE table
COLUMNS TERMINATED BY ','
OPTIONALLY ENCLOSED BY '"'
ESCAPED BY '"'
LINES TERMINATED BY '\n'
IGNORE 1 LINES;
```
