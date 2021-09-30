# 第8課 數據庫基礎 重點內容

## 什麼是數據庫?
就是一個可以檢索和儲存的地方  
由Database Management System(DBMS) + Database所組成。  
DBMS是一個程式,用來控制資料庫的分類及數據的存取 就像是管理員 例如: SQLite, MySQL etc  

## 數據模型
是我們如何定義資料應該如何輸入和與輸出, 例如:顏色, 名字, 年齡
緊記: 一個table只可以有1個**Primary Key(主鍵)**, 它是不能null的

## 關係模型 (Relational model)
意思就是table1 和table之間會存在一種關係, 例如 A工廠**生產** 汽車1 這就是一種關係  
可以生成一個額外的table3 去表現 table1 和table2的關係  
這就會涉及**Foreign Key(外鍵)**, 一般會是其他table中的Primary Key (但不同的是, 它可以null)

## 數據庫類型
關係式資料庫 和 非關係型資料庫  
關係式資料庫: 就是根據關係模型來創建的一種數據庫  
非關係型資料庫: 是一種圖有固定結構的數據庫

## 各種Integrity Constraint
就是一種約束,限制必須遵守  
例如 PK不能NULL而且必須獨特性
