## Установка PostgreSQL на свой ПК

### Установка на Windows

- [Видеоинструкция](https://embed.new.video/uyjUq9B3qYo6BbbkzG71Ny).

- [Ссылка на PostgreSQL для Windows](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads).

### Установка на Linux (на примере Ubuntu 20.04)

- [Видеоинструкция](https://embed.new.video/cRQW4Z2YnxZUxzKRLWwnPF).

- Команды для установки:

```bash
# PostgreSQL
sudo apt update && sudo apt install postgresql-12

# pgAdmin4
wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -
echo "deb http://apt.postgresql.org/pub/repos/apt/ `lsb_release -cs`-pgdg main" |sudo tee  /etc/apt/sources.list.d/pgdg.list
sudo apt update && sudo apt install pgadmin4
```

### Установка на Mac OS X

- [Видеоинструкция](https://clck.ru/32zuuG)

- Команды для установки:

```bash
brew install postgresql

postgres -V

pg_ctl -D /usr/local/var/postgres start

createuser -P -s postgres
```

## Установка DBeaver Community на свой ПК

- [Ссылка на инструкцию](https://github.com/netology-code/sqlpy-code/blob/main/02/DBeaver.md)
- [Ссылка для скачивания](https://dbeaver.io/download/)
