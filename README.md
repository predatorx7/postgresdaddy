# How to use?

```bash
git clone https://github.com/predatorx7/postgresdaddy

cd postgresdaddy;

cp example.env .env;

source .env;

docker compose up -d;

# psql postgres://USERNAME:PASSWORD@SERVER_IP:PORT/DATABASE?sslmode=disable
psql "postgres://$POSTGRES_USER$:$POSTGRES_PASSWORD@localhost:5432/$POSTGRES_DB?sslmode=disable"
```
