# CREATE a database
```
CREATE DATABASE <database_name>;
```

# CREATE an empty table
```
CREATE TABLE <table_name>();
```

# ADD a primary key
```
ALTER TABLE <table_name> ADD PRIMARY KEY(<column_name>);
```

# ADD a composite primary key
```
ALTER TABLE <table_name> ADD PRIMARY KEY(<column1_name>, <column2_name>);
```

# ADD a foreign key
```
ALTER TABLE students ADD FOREIGN KEY(<<column_name>>) REFERENCES <<table_name>>(<<column_name>>);
```

# RENAME table
```
ALTER TABLE <table_name> RENAME TO <table_name>;
```

# TRUNCATE a table
```
TRUNCATE <table_name>;
```

# TRUNCATE multiple table
```
TRUNCATE <table1_name>,<table2_name>,<table2_name>;
```

# DROP a database
```
DROP DATABASE <database_name>;
```

# LIKE , ILIKE , NOT LIKE , NOT ILIKE # ORDER #LIMT
```
SELECT * FROM <table_name> WHERE <column_name> LIKE <pattern> ORDER BY <column_1>[DESC|ASC], [<column_2>[DESC|ASC]] LIMIT <number_of_tuple>;  
pattern   _
pattern   %
```



