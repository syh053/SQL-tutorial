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

<h4> 刪除資料表 </h4>

```
DROP TABLE [table_name];
```

<h4> 查詢當前的資料庫 </h4>

```
SELECT DATABASE();
```

<h4> 切換資料庫 </h4>

```
USE [db_name];
```

<h2> DML 操作資料 </h2>



<h4> 新增資料 (INSERT) </h4>

```
INSERT INTO `drinks` (`name`, `price`, `cost`)
VALUES
('阿華田', 65, 20),
('百香紅茶', 45, 10);
```

<p><img src="https://example.com/my-image.pngLinks to an external site.](https://github.com/syh053/SQL-tutorial/blob/main/photo/%E6%99%82%E9%96%93%E6%A0%BC%E5%BC%8F.jpg" alt="MyImage" />時間格式說明</p>


