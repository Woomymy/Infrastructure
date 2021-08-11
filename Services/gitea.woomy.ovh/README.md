# [Gitea](https://gitea.io)

Self-hosted git service

## Configuration

```sh
DB_TYPE=postgres # You must not change this variable
DB_HOST=db:5432 # Change if db service is renamed
DB_NAME=<NAME_OF_DB>
DB_USER=<NAME_OF_DB_USER>
DB_PASSWD=<DB_PASSWORD>
POSTGRES_USER=<NAME_OF_DB_USER> # $DB_NAME
POSTGRES_PASSWORD=<DB_PASSWORD> # $DB_PASSWD
POSTGRES_DB=<NAME_OF_DB> # $DB_NAME
```

