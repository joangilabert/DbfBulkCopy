# DbfBulkCopy

Command line application to bulk copy from DBF files to MS SqlServer

Usage:

```
DbfBulkCopy 1.0.0
Copyright (C) 1 author

  --server             Required. The database server

  --database           Required. The name of the database

  --userid             Required. The UserID used to connect to the database server

  --password           Required. The password used to connect to the database server

  --dbf                Required. Path to the DBF file to import

  --table              Required. The name of the database table to import into

  --bulkcopytimeout    (Default: 30) The connection timeout used in the bulk copy operation

  --truncate           (Default: false) Whether to truncate the table before copying

  --help               Display this help screen.

  --version            Display version information.
```
