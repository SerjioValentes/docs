### Переключиться на учетную запись postgres
    sudo -i -u postgres
### Create SuperUser 
    sudo -u postgres createuser -s [name]
### Change password for user
    \password <userName>
### Подключиться к psql
    psql -U postgres
### Вывод пользователей с правами
    \du
### Create database from 
    postgres@username:$ createdb dbname

## LINKS:
[How to install postgres to Ubuntu server](https://selectel.ru/blog/tutorials/how-to-install-and-use-postgresql-on-ubuntu-20-04/)