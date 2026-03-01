# PostgresScripts

Useful Postgres scripts and related information about Postgres.

## Check if Postgres is running and accepting connections

```pg_isready -h localhost -p 5432```

Which should give a response like this:

```localhost:5432 - accepting connections```

Source: https://www.beekeeperstudio.io/blog/how-to-check-if-postgresql-is-running/

## Check if the Postgres service is running on Linux

```ps aux | grep postgres```

    -- Source - https://stackoverflow.com/a/5665726
    -- Posted by grantk, modified by community. See post 'Timeline' for change history
    -- Retrieved 2026-03-01, License - CC BY-SA 3.0

## See Also

Useful SQL Server scripts.

https://github.com/richardlucas761/SQLScripts
