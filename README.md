# TP1 DevOps – Docker

Conteneurisation d'une application Spring Boot (`simpleapi`) avec sa base PostgreSQL (`db`) et un reverse proxy Apache (`httpd`), orchestrés par Docker Compose. `hello` contient le premier exercice (Hello World Java en conteneur).

## Lancement

```bash
cp .env.example .env   # puis renseigner les valeurs
docker compose up --build
```

L'application est exposée sur le port 80 via `httpd`.
