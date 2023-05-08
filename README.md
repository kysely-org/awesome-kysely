<p align="center">
  <img src="art.png" />
  <br>
  <span>A curated list of <a href="https://kysely.dev" target="_blank">Kysely</a> resources, tools, utilities and applications.</span>
</p>

<br>

## Contents

- [Adapters](#adapters)
- [Addons](#addons)
- [Articles](#articles)
- [Dialects](#dialects)
- [ORMs](#orms)
- [Templates](#templates)
- [Type Generators](#type-generators)
- [Videos](#videos)

## Adapters

- [nestjs-kysely](https://github.com/kazu728/nestjs-kysely) - [Kysely](https://kysely.dev) module for [NestJS](https://nestjs.com/).

## Addons

- [kysely-paginate](https://github.com/charlie-hadden/kysely-paginate) - Pagination helpers for use with [Kysely](https://kysely.dev).
- [kysely-params](https://github.com/jtlapp/kysely-params) - A utility for parameterizing compiled [Kysely](https://kysely.dev) queries.

## Articles

- [Kysely - A type-safe SQL query builder for typescript](https://www.jakso.me/blog/kysely-a-type-safe-sql-query-builder-for-typescript) - A blog post by [koskimas](https://github.com/koskimas), the creator of [Kysely](https://kysely.dev). Letting the world know, way back in 2021, what is [Kysely](https://kysely.dev), its inspiration, design principles, etc.
- [Typesafe Database Queries on the Edge](https://www.nexxel.dev/blog/typesafe-database) - The groundbreaking blog post by [nexxel](https://twitter.com/nexxeln) that set the stage for the [Prisma](https://www.prisma.io) + [Kysely](https://kysely.dev) + [Planetscale](https://planetscale.com)'s DatabaseJS serverless driver usage pattern. Inspired the [prisma-kysely](https://github.com/valtyr/prisma-kysely) adapter.
- [Build TypeSafe Node API using tRPC, Fastify, Kysely and Atlas CLI](https://dev.to/franciscomendes10866/build-typesafe-node-api-using-trpc-fastify-kysely-and-atlas-cli-580c) - A blog post by [Francisco Mendes](https://github.com/FranciscoMendes10866) on combining [Kysely](https://kysely.dev), [tRPC](https://trpc.io), [Fastify](https://www.fastify.io) and [Atlas](https://atlasgo.io/) to build a robust, type-safe CRUD API.
- [Crafting the Perfect T3 Stack: My Journey with Kysely, Atlas, and Clerk](https://eliasson.me/articles/crafting-the-perfect-t3-stack-my-journey-with-kysely-atlas-and-clerk) - A blog post by [Elias Eliasson](https://twitter.com/elitasson) on how he built his [T3](https://create.t3.gg) inspired stack with [Kysely](https://kysely.dev), [Atlas](https://atlasgo.io/) and [Clerk](https://clerk.dev).
- [Kysely dialect for PlanetScale](https://depot.dev/blog/kysely-dialect-planetscale) - A blog post by [Jacob Gillespie](https://twitter.com/jacobwgillespie) on how [Depot](https://depot.dev) adopted [Kysely](https://kysely.dev) and [PlanetScale](https://planetscale.com/) and created the [Planetscale dialect](https://github.com/depot/kysely-planetscale).
- [Simple CQRS in NodeJS with Typescript](https://itnext.io/simple-cqrs-in-nodejs-with-typescript-6da6d3e8a420) - A blog post by Illija on how to implement a simple CQRS pattern with query models using [Kysely](https://kysely.dev).
- [Kysely and CockroachDB](https://morgans-blog.deno.dev/kysely-crdb) - A blog post by [Morgan Winslow](https://github.com/mowinslow2) on [Kysely](https://kysely.dev) and how to use it with [CockroachDB](https://www.cockroachlabs.com).
- [Type-safe S3 Select queries with Kysely](https://dev.to/kumo/type-safe-s3-select-queries-with-kysely-4ge0) - A blog post by [Thomas Aribart](https://twitter.com/aribartt) on how to query [AWS S3](https://aws.amazon.com/s3) buckets, and how to do it in a type-safe manner with [Kysely](https://kysely.dev). Inspired the [S3 Select dialect](https://github.com/igalklebanov/kysely-s3-select).
- [Typescript で SQL を叩く方法を整理する](https://zenn.dev/moekidev/articles/d3db4dc362b93d) - A blog post by [moekidev](https://twitter.com/moekidev) about trying out [Kysely](https://kysely.dev) with [Prisma](https://www.prisma.io) and [Vercel Postgres](https://vercel.com/postgres).

## Dialects

- [kysely-data-api](https://github.com/serverless-stack/kysely-data-api) - This library adds [AWS RDS Data Api](https://docs.aws.amazon.com/rdsdataservice/latest/APIReference/Welcome.html) support for [Kysely](https://kysely.dev). It has support for both [MySQL](https://www.mysql.com) and [Postgres](https://www.postgresql.org).
- [kysely-planetscale](https://github.com/depot/kysely-planetscale) - A [Kysely](https://kysely.dev) dialect for [PlanetScale](https://planetscale.com), using the [PlanetScale](https://planetscale.com) serverless driver for JavaScript.
- [kysely-d1](https://github.com/aidenwallis/kysely-d1) - [Kysely](https://kysely.dev) dialect for [Cloudflare D1](https://developers.cloudflare.com/d1).
- [kysely-neon](https://github.com/seveibar/kysely-neon) - [Kysely](https://kysely.dev) dialect for [Neon](https://neon.tech) serverless [Postgres](https://www.postgresql.org).
- [kysely-surrealdb](https://github.com/igalklebanov/kysely-surrealdb) - [Kysely](https://kysely.dev) dialects, plugins and other goodies for [SurrealDB](https://surrealdb.com). SurrealQL is based on SQL, so why not? :trollface:

## ORMs

## Templates

- [Acme Corp](https://acme-corp.jumr.dev) - Your all-in-one, enterprise ready starting point. Full-stack Typesafety with [tRPC](https://trpc.io/), [Next.js](https://nextjs.org), and [React](https://react.dev) Server Components. Typesafe database access using [Kysely](https://kysely.dev) as query builder, and [Prisma](https://www.prisma.io) for schema management.
- [Vercel Postgres + Kysely Next.js Starter](https://vercel.com/templates/next.js/postgres-kysely) - Simple [Next.js](https://nextjs.org) template that uses [Vercel Postgres](https://vercel.com/postgres) as the database and [Kysely](https://kysely.dev) as the query builder.

## Type Generators

- [kysely-codegen](https://github.com/RobinBlomberg/kysely-codegen) - Generate [Kysely](https://kysely.dev) type definitions from your database.
- [prisma-kysely](https://github.com/valtyr/prisma-kysely) - Generate [Kysely](https://kysely.dev) types directly from your [Prisma](https://www.prisma.io) schema.

## Videos

- [Type-Safe SQL on the Edge with Kysely](https://youtu.be/zd9a_Lk3jAc) - [Supabase](https://supabase.com) Edge Functions can connect directly to your [Postgres](https://www.postgresql.org) database to execute SQL Queries. [Kysely](https://kysely.dev) is a type-safe and autocompletion-friendly typescript SQL query builder. Combining [Kysely](https://kysely.dev) with [Deno Postgres](https://deno-postgres.com) provides a neat developer experience for interacting directly with your [Postgres](https://www.postgresql.org) database.
