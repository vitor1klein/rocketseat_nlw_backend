NLW - Spacetime
Node Version: 18.x

Linha do tempo
npm init -y (Cria o package.json)
npm install typescript -D
npm install tsx -D
npm install @types/node -D
npx tsc --init (Cria o arquivo de configuração do typescript, alterar para es2020)
Criar o script 'dev' para start: tsx src/server.ts
npm run dev



--para migração do banco
npx prisma migrate dev

--para migração com reset do banco
npx prisma migrate reset

--para abrir o prisma studio
npx prisma studio

--plugin de CORS
npm i @fastify/cors