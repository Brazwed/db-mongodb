# db-mongodb

MongoDB 7 Docker container pré-configurado. Pronto pra usar, com autenticação.

## Uso rápido

```bash
git clone https://github.com/Brazwed/db-mongodb.git
cd db-mongodb
docker compose up -d
```

## Conexão padrão

```
Host:     localhost
Porta:    27017
Usuário:  mongodb_user
Senha:    mongodb_dev_2026

mongosh mongodb://mongodb_user:mongodb_dev_2026@localhost:27017/devdb
```

## Configuração

Edite `.env` (criado automaticamente de `.env.example`):

```env
MO_PORT=27017
MO_USER=mongodb_user
MO_PASS=mongodb_dev_2026
MO_DB=devdb
```

## Parte do Database Toolkit

Este repositório pode ser usado standalone ou junto com outros bancos via [Database](https://github.com/Brazwed/Database).
