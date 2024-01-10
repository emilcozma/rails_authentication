# A Simple Authentication with Ruby On Rails 

## Prerequisites
- docker
- docker compose

## To build the image:
```bash
docker build -t rails-toolbox -f Dockerfile.rails .
```

## Running Everything
```bash
docker compose up --build
```

## Initialize the Database
```bash
docker compose run --rm app rake db:reset
docker compose run --rm app rake db:create
docker compose run --rm app rake db:migrate
```

## Testing It Out

Head over to http://localhost:8020

### Welcome screen

### Sign up screen

### Sign in screen

### Profile screen