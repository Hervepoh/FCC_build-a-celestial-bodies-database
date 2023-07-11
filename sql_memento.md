# CREATE a database
```
CREATE DATABASE <database_name>;
```

# RENAME a database
```
ALTER DATABASE <database_name> RENAME TO <new_database_name>;
```

# DROP a database
```
DROP DATABASE <database_name>;
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

# ADD a foreign key using an existing Column 
```
ALTER TABLE students ADD FOREIGN KEY(<<column_name>>) REFERENCES <<table_name>>(<<column_name>>);
```

# ADD a foreign key 
```
ALTER TABLE table_name ADD COLUMN column_name DATATYPE REFERENCES <<referenced_table_name>>(<<referenced_column_name>>);
```

# ADD a unique constraint 
```
ALTER TABLE table_name ADD UNIQUE(<<column_name>>);
```

# UPDATE a column
```
ALTER TABLE table_name ALTER COLUMN column_name SET NOT NULL;
```
RENAME A COLUMN 
```
ALTER TABLE more_info RENAME COLUMN height TO height_in_cm
```

# DROP a constraint
```
ALTER TABLE students FROP CONSTRAINT <<constraint_name>> ;
```

# RENAME table
```
ALTER TABLE <table_name> RENAME TO <new_table_name>;
```

# TRUNCATE a table
```
TRUNCATE <table_name>;
```

# TRUNCATE multiple table
```
TRUNCATE <table1_name>,<table2_name>,<table2_name>;
```

# LIKE , ILIKE , NOT LIKE , NOT ILIKE # ORDER #LIMT
```
SELECT * FROM <table_name> WHERE <column_name> LIKE <pattern> ORDER BY <column_1>[DESC|ASC], [<column_2>[DESC|ASC]] LIMIT <number_of_tuple>;  
pattern   _
pattern   %
```
# CEIL , FLOOR , ROUND , SUM ,AVG , MAX , MIN 


