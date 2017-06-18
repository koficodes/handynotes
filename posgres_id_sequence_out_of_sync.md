```sql
SELECT setval(pg_get_serial_sequence('your_table_name', 'id'), (SELECT MAX(id) FROM your_table_name));
```
