## Terminal

```bash


# dev
npm i typescript -D
npm i tsx -D
npm i @types/node -D
npm i prisma -D
npm i dotenv -D

npm i eslint -D
npm i @rocketseat/eslint-config -D

# prod
npm i fastify
npm i @prisma/client
npm i axios
npm i @fastify/jwt
npm i @fastify/multipart
npm i @fastify/static

npx tsc --init
npx prisma init --datasource-provider SQLite

```

##TSC

```json
{
  "compilerOptions": {
    "target": "es2020",
    "module": "commonjs",
    "esModuleInterop": true,
    "forceConsistentCasingInFileNames": true,
    "strict": true,
    "skipLibCheck": true
  }
}
```

##PackageJson

```json
"scripts": {
    "dev": "tsx watch src/server.ts",
    "lint": "eslint src --ext .ts --fix",
    "migrate":"prisma migrate dev"
  },
```

##Eslint

```json
{
  "extends": ["@rocketseat/eslint-config/node"]
}
```
