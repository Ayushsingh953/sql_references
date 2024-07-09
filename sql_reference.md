
# Database

**Create**
```sql
CREATE DATABASE database_name;
```

**Drop**
```sql
DROP DATABASE database_name;
```

**Rename**
```sql
ALTER DATABASE database_name RENAME TO new_name;
```

# Table

**Create**
```sql
CREATE TABLE table_name();
```

**Drop**
```sql
DROP TABLE table_name;
```

**Rename**
```sql
ALTER TABLE table_name RENAME TO new_name;
```

# Row

**Insert**
```sql
INSERT INTO table_name(columns) VALUES(values);
```

**Update**
```sql
UPDATE table_name SET column_name = new_value WHERE condition;
```

**Delete**
```sql
DELETE FROM table_name WHERE condition;
```

# Column

**Add**
```sql
ALTER TABLE table_name ADD COLUMN column_name;
```

**Drop**
```sql
ALTER TABLE table_name DROP COLUMN column_name;
```

**Rename**
```sql
ALTER TABLE table_name RENAME COLUMN column_name TO new_name;
```

**Primary** Key
```sql
ALTER TABLE table_name ADD PRIMARY KEY(column_name);
```

**Foreign** Key
```sql
ALTER TABLE table_name ADD FOREIGN KEY(column_name) REFERENCES table_name(column_name);
```
