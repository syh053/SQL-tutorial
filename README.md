# SQL-tutorial

<h3><a href="https://www.db-fiddle.com/" target="_blank"> DB Fiddle 線上測試 </a></h3>
<h3><a href="https://wtools.io/generate-sql-create-table#google_vignette" target="_blank"> SQL 指令產生器 </a></h3>


<h4> 建立資料庫並設定編碼 </h4>

```
CREATE DATABASE drink_store
CHARACTER SET utf8mb4
COLLATE utf8mb4_unicode_ci;
```




<h4> 產生 TABLE </h4>

```
CREATE TABLE `drinks` (
  `id`    int(11)      unsigned NOT NULL AUTO_INCREMENT,
  `name`  varchar(20)           NOT NULL,
  `price` int(11)      unsigned NOT NULL,
  `cost`  int(11)      unsigned NOT NULL,
  PRIMARY KEY (`id`)
);
```

<h4> 查詢資料表結構的兩種方式 </h4>

```
EXPLAIN [table_name];
```

```
SHOW FULL FIELDS FROM [table_name];
```

