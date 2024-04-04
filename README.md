# SQL-tutorial

<h3><a href="https://www.db-fiddle.com/" target="_blank"> DB Fiddle 線上測試 </a></h3>
<h3><a href="https://wtools.io/generate-sql-create-table#google_vignette" target="_blank"> SQL 指令產生器 </a></h3>


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

```REATE TABLE `drinks` (
  `id`    int(11)      unsigned NOT NULL AUTO_INCREMENT,
  `name`  varchar(20)           NOT NULL,
  `price` int(11)      unsigned NOT NULL,
  `cost`  int(11)      unsigned NOT NULL,
  PRIMARY KEY (`id`)
);
