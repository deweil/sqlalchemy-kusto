# sqlalchemy-kusto
Kusto dialect for SQLAlchemy

---
File structure https://github.com/zzzeek/sqlalchemy/blob/master/README.dialects.rst#dialect-layout

Inspired by https://github.com/preset-io/elasticsearch-dbapi

One file example from PyDruid https://github.com/druid-io/pydruid/blob/master/pydruid/db/sqlalchemy.py

Snow-flake example https://github.com/snowflakedb/snowflake-sqlalchemy


To make dialect work, we should have db api over Kusto database. 
See https://www.python.org/dev/peps/pep-0249
Kusto db api path: sqlalchemy_kusto/dbapi.py

---
Issue that inspired this solution https://github.com/apache/superset/issues/10646
