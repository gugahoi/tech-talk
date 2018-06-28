# DBs

## Relational Databases

ERDs
Relationships: 1:1, M:1, 1:M, M:M
Schema
Storage Engines:
- MyISAM
- - no indexes
- - useful for large ammounts of data (no indeces mean it's more performant at large scale)
- InnoDB
- - indexes
- - useful for somewhat smaller ammount of data

EXPLAIN command:
    Check query performance
    Shows keys used, algorithms, how many rows

Commands:
- DDL: create, drop, alter, truncate, rename
- DML: insert, update, select, delete
- DCL: grant, revoke
- TCL: commit, rollback

Next:
- Normalization
- Indexes (need to read up)?
- SlowQuery.log
- Filesort <- type of algorithm used to get data from table (which other ones are there?)
