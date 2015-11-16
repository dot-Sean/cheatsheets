### Rename column name

```sql
ALTER TABLE mytable CHANGE myColumn newColumnName VARCHAR(255)
```

### Add column

```sql
ALTER TABLE myTable ADD newColumn VARCHAR(255) AFTER someColumn;
```
