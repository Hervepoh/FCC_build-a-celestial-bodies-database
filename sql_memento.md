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
ALTER TABLE <table_name> ADD PRIMARY KEY(<column_name>, <column_name>);
```

# ADD a foreign key
```
ALTER TABLE students ADD FOREIGN KEY(<<column_name>>) REFERENCES <<table_name>>(<<column_name>>);
```
