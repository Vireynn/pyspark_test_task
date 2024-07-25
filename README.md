# pyspark_test_tast

### Датафрейм products
```
+----------+------------+
|product_id|product_name|
+----------+------------+
|         1|   Product A|
|         2|   Product B|
|         3|   Product C|
+----------+------------+
```

### Датафрейм categories
```
+-----------+-------------+
|category_id|category_name|
+-----------+-------------+
|          1|    Category1|
|          2|    Category2|
+-----------+-------------+
```

### Вывод
```
+------------+-------------+
|product_name|category_name|
+------------+-------------+
|   Product C|         NULL|
|   Product A|    Category1|
|   Product B|    Category1|
|   Product A|    Category2|
+------------+-------------+
```
