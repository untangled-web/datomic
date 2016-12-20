0.4.12
------
- Implemented IDeref on DatabaseComponent, which returns a datomic.db.Db instance.
- Updated the query function in untangled.datomic.core to support multiple data sources. Data sources can be any of
a Datomic Connection, Datomic Db, and Untangled DatabaseComponent.

0.4.11
------
- Bug fix on migration system (calling migration functions that should not have been called)
- More refcas work

0.4.9
-----
- Changed seeding to allow exceptions to propagate up

0.4.8
-----
- Added dummy logger to avoid crashes


0.4.4 - March 2, 2016
---------------------
- Updated readme
- Updated dependencies
