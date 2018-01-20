Simple image for testing connections to PostgeSQL databases from within a Docker container

Usage:
```
docker run -e PGHOST=host.example.org -e PGUSER=user1 PGDATABASE=exampledb PGPORT=5432 PGPASSWORD=password -ti mans0954/psql
```
