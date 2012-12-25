mysql2h2-converter
==================

A MySQL to H2 SQL conversion library written in Java.

For the moment, you can parse a MySQL dump and convert it to H2 statements.

Next steps are:
- implement other statements (SELECT, UPDATE...)
- provide samples for an on-the-fly conversion with datasource-proxy http://code.google.com/p/datasource-proxy/

Other ideas:
- support of large SQL files: parse and convert statements one by one instead of loading everything in memory
- look at jOOQ http://www.jooq.org/ to see if it can be used to model the DML statements and Liquibase http://www.liquibase.org/
  for the DDL part