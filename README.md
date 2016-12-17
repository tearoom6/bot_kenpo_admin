# BotKenpoAdmin

Rails application to management BotKenpo.

## Configuration

## Database creation

Create Postgre database for development use.

```sql
CREATE USER bot_kenpo with encrypted password 'bot_kenpo';
CREATE DATABASE bot_kenpo_development;
GRANT ALL PRIVILEGES ON DATABASE bot_kenpo_development TO bot_kenpo;
```

## How to run the development server

```sh
$ bundle exec rails s
```

