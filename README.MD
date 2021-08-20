# Backend

This is the backend for the Player 2 app.

## Prerequisites
Ensure you have Node and Docker installed.

## Installation

1.  Install the node modules.

```bash
npm install
```

2. Install nodemon for live reload.
```bash
npm install -g nodemon
```

3. Make a copy of .env.example to .env
4. Get the database up.
```bash
docker-compose -f "./docker-compose.yml" up -d --build
```

Check that the database is up if you see the Docker image when you run this command.
```bash
docker ps
```


## Usage

```bash
npm run serve
```