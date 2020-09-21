# Postgres/PGAdmin/FlyWay

Configuração simples de um docker-compose para subir um banco postgres a partir de um diretório com scripts versionados usando o FlyWay e com a ferramenta PGAdmin configurada.

## Configuração

    Usuário padrão: postgres
    
    Váriaveis configuradas no arquivo '.env'

    Nome do banco: PG_DB
    Senha do banco: PG_PASSWORD

    E-mail padrão do PGAdmin: PGADMIN_EMAIL
    Senha do PGAdmin: PGADMIN_PASSWORD

    Local dos Scripts para o Flyway: DIR_PG_SCRIPTS

## Referências

* [PostgreSQL Docker - Quick reference](https://github.com/docker-library/docs/blob/master/postgres/README.md)

* [FlyWay - Versioned Migrations](https://flywaydb.org/documentation/migrations#naming-1)

* [PGAdmin - Import/Export Servers](https://www.pgadmin.org/docs/pgadmin4/development/import_export_servers.html)
