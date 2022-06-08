# IgniteDeliver

A delivery api in node, using ORM Prisma and auth JWT

## Set Enviroment

```bash
   $ cp .env.example .env
```

## Config settings .env

```
   DATABASE_URL="postgresql://USER:PASSWORD@HOST:PORT/DATABASE"
```

## Installation

```bash
   $ yarn install
```

## Running the app

```bash
    # run the migrations
    $ yarn prisma migrate dev

    # watch mode
    $ yarn dev
```

## Prisma Studio

```bash
    # access prisma studio
    $ yarn prisma studio
```
