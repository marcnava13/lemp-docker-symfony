## Docker LEMP STACK

Run Nginx, PHP 7 and Mysql using [Docker]

### Requirements
Install [Docker] and [Compose]

### Installation

Step 1: First, clone this repository:

```bash
$ git clone git@github.com:marcnava13/lemp-docker-symfony.git
```

Step 2: Create a .env from the .env.dist file. Adapt it according to your symfony application

```bash
cp .env.dist .env
```

Step 3: Change the password for the database from .env file that you'll find in the root project:

```bash
MYSQL_ROOT_PASSWORD=password
```

Step 4: Then, run:

```bash
$ docker-compose up -d
```

You are done, you can visit your application on the following URL: `http://localhost:8080`

[Docker]:                      https://www.docker.io/
[Compose]:                     http://docs.docker.com/compose/install/