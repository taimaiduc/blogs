The most commonly used storage engine in MySQL are MyISAM and InnoDB. With these storage engine there are some advantages and disadvantages. As you all know, the default storage engine chosen by MySQL database is MyISAM.


The main difference between MyISAM and INNODB are :

-   MyISAM does not support transactions by tables while InnoDB supports.
-   There are no possibility of row-level locking, relational integrity in MyISAM but with InnoDB this is possible. MyISAM has table-level locking.
-   InnoDB does not support FULLTEXT index while MyISAM supports.
-   Performance speed of MyISAM table is much higher as compared with tables in InnoDB.
-   InnoDB is better option while you are dealing with larger database because it supports transactions, volume while MyISAM is suitable for small project.
-   As InnoDB supports row-level locking which means inserting and updating is much faster as compared with MyISAM.
-   InnoDB supports ACID (Atomicity, Consistency, Isolation and Durability) property while MyISAM does not support.
-   In InnoDB table,AUTO_INCREMENT field is a part of index.
-   Once table in InnoDB is deleted then it can not re-establish.
-   InnoDB does not save data as table level so while implementation of select count(*) from table will again scan the whole table to calculate the number of rows while MyISAM save data as table level so you can easily read out the saved row number.
-   MyISAM does not support FOREIGN-KEY referential-integrity constraints while InnoDB supports.
