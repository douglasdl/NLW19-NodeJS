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