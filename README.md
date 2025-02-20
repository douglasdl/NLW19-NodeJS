# NLW19-NodeJS

- [NLW Documents](https://efficient-sloth-d85.notion.site/NLW-Connect-337b47bcef1640fc9a536f66dd45d8f1)
- [NodeJS](https://nodejs.org/en)
- [NPM](https://docs.npmjs.com/)
- [NVM](https://github.com/nvm-sh/nvm)
- [VS Code](https://code.visualstudio.com/download)
  VS Code Extensions:
  - [Omni Theme](https://marketplace.visualstudio.com/items?itemName=rocketseat.theme-omni)
  - [Symbols](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.symbols)
  - [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)
  - [Biome](https://marketplace.visualstudio.com/items?itemName=biomejs.biome)

- Databases
  - [Redis](https://redis.io/)
  - [PostgreSQL](https://www.postgresql.org/)

- [Docker](https://docs.docker.com/)
- [Docker Installation](https://efficient-sloth-d85.notion.site/NLW-Connect-337b47bcef1640fc9a536f66dd45d8f1)
- [Docker Hub](https://hub.docker.com/)
  - [PosgreSQL image](https://hub.docker.com/r/bitnami/postgresql)
  - [Redis image](https://hub.docker.com/r/bitnami/redis)
- [Hello World - Docker Image](https://hub.docker.com/_/hello-world)

Main Docker commands:
```sh
docker pull hello-world
docker run hello-world
docker images
docker ps
docker ps -a
docker run redis
docker run -d redis
docker start redis
docker stop redis
```

- [Fastify](https://fastify.dev/)
- Middlewares
  - CORS
- [Zod](https://zod.dev/)
- [Biome](https://biomejs.dev/)

Create the Project:
```sh
npm init -y
```

Install the dependencies:
```sh
npm i fastify
npm i tsx typescript @types/node -D
npm i @fastify/cors
npm i zod
npm i fastify-type-provider-zod
npm i @fastify/swagger @fastify/swagger-ui
npm i @biomejs/biome -D
npm i ioredis
npm i postgres drizzle-orm
npm i drizzle-kit -D
npm i tsup -D
```

- [tsconfig - bases](https://github.com/tsconfig/bases)
Create the "tsconfig.json":
```sh
npx tsc --init
```

Run the server.ts:
```sh
npx tsx src/server.ts
```

Download the Docker images:
```sh
docker pull bitnami/postgresql
docker pull bitnami/redis
```


Run the Docker Compose:
```sh
docker compose up -d
```

Check if the containers are running
```sh
docker ps
```

Check the container logs informing the container id:
```sh
docker logs 3d992806efe4
docker logs c55e08bbd9a4
```

Create the SQL files and Generate the Drizzle migrations:
```sh
npx drizzle-kit generate
npx drizzle-kit migrate
```

## Hostages

- [Neon](https://neon.tech): Postgres
- [Upstash](https://upstash.com/): Redis
- [Render](https://render.com/docs/deploy-node-express-app): Node.js