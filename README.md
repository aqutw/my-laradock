# Commands
docker-compose up -d nginx mysql adminer
docker-compose down
docker-compose exec workspace bash

# Links
http://127.0.0.1:8099 -> Laravel Web
http://127.0.0.1:8081 -> Adminer DB Client

# Folders/Files
cat ../lalara/.env

DB_CONNECTION=mysql
DB_HOST=mysql
DB_PORT=3306
DB_DATABASE=default
DB_USERNAME=default
DB_PASSWORD=secret

# Refs
https://jsnwork.kiiuo.com/archives/3151/
