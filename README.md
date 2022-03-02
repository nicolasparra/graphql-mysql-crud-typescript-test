### GraphQL MySQL Typescript CRUD TEST

### Installation

```
npm i
npm run build
npm start
```

for development:

```
npm run dev
```

#### Environment variables

```
DB_HOST=localhost
DB_PORT=3306
DB_NAME=usersdb
DB_USERNAME=root
DB_PASSWORD=password
```

#### MySQL Docker

```bash
docker run --name mymysql -e MYSQL_ROOT_PASSWORD=password -d -p 3306:3306 -e default-authentication-plugin=mysql_native_password mysql
```

```bash
docker exec -it mmysql bash
```

```bash
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';

ALTER USER 'root' IDENTIFIED WITH mysql_native_password BY 'password';
```

```bash
flush privileges;
```

#### MySQL Docker-Compose

```bash
docker-compose up -d
```
