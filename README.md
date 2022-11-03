# nlw-copa
Next Level Week - Copa Edition

### Tecnologias Back-end
- Fastify
- Prisma (ORM)
- SQLite (npx prisma init --datasource-provider SQLite)

Cria uma Migration (exemplo: criação da tabela)
- npx prisma migrate dev

Visualizar o banco de dados via navegador
- npx prisma studio

Gerando o Diagrama ERD
- instalação: npm i prisma-erd-generator @mermaid-js/mermaid-cli -D
- npx prisma generate