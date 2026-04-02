# db-mongodb

MongoDB 7 Docker container pre-configured. Ready to use, with authentication.

## Quick Start

```bash
git clone https://github.com/Brazwed/db-mongodb.git
cd db-mongodb
docker compose up -d
```

## Default Connection

```
Host:     localhost
Port:     27017
User:     mongodb_user
Pass:     mongodb_dev_2026

mongosh mongodb://mongodb_user:mongodb_dev_2026@localhost:27017/devdb
```

## Configuration

Edit `.env` (created automatically from `.env.example`):

```env
MO_PORT=27017
MO_USER=mongodb_user
MO_PASS=mongodb_dev_2026
MO_DB=devdb
```

## Part of Database Toolkit

This repo can be used standalone or with other databases via [Database Toolkit](https://github.com/Brazwed/Database).
