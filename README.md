### Source

> https://www.prisma.io/docs/orm/overview/introduction/what-is-prisma

### This Git

> https://github.com/samedan/2501_Vercel_Postgres_Prisma

# Added Postgres DBB to project

# Added Prisma schema

> /prisma/schema.prisma

> npx prisma db push

# DBB in sync, Prisma Studio

> npx prisma studio
>
> > ![Prisma](https://github.com/samedan/2501_Vercel_Postgres_Prisma/blob/main/_printscreens/01printscreen.jpg)

# Prisma client

> npm install @prisma/client

### Add Prisma Client to own Schema

> npx prisma generate

> mkdir lib

> /lib/prisma.ts -> export default prisma;

### View Content from dbb

> /pages/index.tsx -> import prisma from "../lib/prisma";
> /pages/p/[id].tsx -> import prisma from "../lib/prisma";
