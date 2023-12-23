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
- [CLIs](#clis)
- [Dialects](#dialects)
- [ORMs](#orms)
- [Plugins](#plugins)
- [Templates](#templates)
- [Tools](#tools)
- [Type Generators](#type-generators)
- [Videos](#videos)

## Adapters

| name | description | url | status |
| :--- | :--- | :---: | :--- |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/69392ade-a58b-4d13-bf7d-e42ee863b6d5" height="24px" width="24px" /> @auth/kysely-adapter | Official [Auth.js](https://authjs.dev) adapter for [Kysely](https://kysely.dev). | [link](https://authjs.dev/reference/adapter/kysely) | ![npm](https://img.shields.io/npm/dw/@auth/kysely-adapter?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/@auth/kysely-adapter?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/eac6f115-f2d2-45a8-a6a2-9e21824682ec" height="24px" width="24px" /> nestjs-kysely | [Kysely](https://kysely.dev) module for [NestJS](https://nestjs.com/). | [link](https://github.com/kazu728/nestjs-kysely) | ![npm](https://img.shields.io/npm/dw/nestjs-kysely?style=flat-square) <br/>![GitHub stars](https://img.shields.io/github/stars/kazu728/nestjs-kysely?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/nestjs-kysely?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/60297077-dfb1-4fc3-b6bc-e8c310836042" height="24px" width="24px" /> feathers-kysely | [FeathersJS](https://feathersjs.com) SQL service adapter built with [Kysely](https://kysley.dev). | [link](https://github.com/marshallswain/feathers-kysely) | ![npm](https://img.shields.io/npm/dw/feathers-kysely?style=flat-square) <br/>![GitHub stars](https://img.shields.io/github/stars/marshallswain/feathers-kysely?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/feathers-kysely?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/3e169b5d-31a8-4f93-b7f0-742eca7bbe3a" height="24px" width="24px" /> kysely-sequelize | A toolkit (dialect, type translators, etc.) that allows using your existing [Sequelize](https://sequelize.org/docs/v6) instance with [Kysely](https://kysely.dev). | [link]() | ![npm](https://img.shields.io/npm/dw/kysely-sequelize?style=flat-square) <br/>![GitHub stars](https://img.shields.io/github/stars/igalklebanov/kysely-sequelize?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/kysely-sequelize?style=flat-square) |


## Addons

- [kysely-paginate](https://github.com/charlie-hadden/kysely-paginate) - Pagination helpers for use with [Kysely](https://kysely.dev). ![npm](https://img.shields.io/npm/dw/kysely-paginate?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/charlie-hadden/kysely-paginate?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-paginate?style=flat-square)
- [kysely-params](https://github.com/jtlapp/kysely-params) - A utility for parameterizing compiled [Kysely](https://kysely.dev) queries. ![npm](https://img.shields.io/npm/dw/kysely-params?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/jtlapp/kysely-params?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-params?style=flat-square)

## Articles

- [Kysely - A type-safe SQL query builder for typescript](https://www.jakso.me/blog/kysely-a-type-safe-sql-query-builder-for-typescript) - A blog post by [koskimas](https://github.com/koskimas), the creator of [Kysely](https://kysely.dev). Letting the world know, way back in 2021, what is [Kysely](https://kysely.dev), its inspiration, design principles, etc.
- [Typesafe Database Queries on the Edge](https://www.nexxel.dev/blog/typesafe-database) - The groundbreaking blog post by [nexxel](https://twitter.com/nexxeln) that set the stage for the [Prisma](https://www.prisma.io) + [Kysely](https://kysely.dev) + [Planetscale](https://planetscale.com)'s DatabaseJS serverless driver usage pattern. Inspired the [prisma-kysely](https://github.com/valtyr/prisma-kysely) adapter.
- [Type-safe SQL queries with Kysely and PostgreSQL](https://wanago.io/2023/08/07/api-nestjs-kysely-postgresql) - A blog post by [Marcin Wanago](https://twitter.com/wanago_io) that covers introducing [Kysely](https://kysely.dev) and [PostgreSQL](https://www.postgresql.org/) to a [NestJS](https://nestjs.com/) project from the ground up and in great detail.
- [One-to-one relationships with the Kysely query builder](https://wanago.io/2023/08/14/api-nestjs-kysely-one-to-one/) - A blog post by [Marcin Wanago](https://twitter.com/wanago_io) that covers how to manage one-to-one SQL relationships between tables using [Kysely](https://kysely.dev).
- [Building a PageSpeed Monitoring Service Using Remix, Kysely, and Litestream](https://www.joseferben.com/posts/a-pagespeed-monitoring-service-using-remix-kysely-and-litestream) - A great blog post by [Josef Erben](https://twitter.com/joseferben) that provides a high-level overview of an architecture combining [Kysely](https://kysely.dev) and [Remix](https://remix.run), and shows trade-offs of design decisions made.
- [Build TypeSafe Node API using tRPC, Fastify, Kysely and Atlas CLI](https://dev.to/franciscomendes10866/build-typesafe-node-api-using-trpc-fastify-kysely-and-atlas-cli-580c) - A blog post by [Francisco Mendes](https://github.com/FranciscoMendes10866) on combining [Kysely](https://kysely.dev), [tRPC](https://trpc.io), [Fastify](https://www.fastify.io) and [Atlas](https://atlasgo.io/) to build a robust, type-safe CRUD API.
- [Crafting the Perfect T3 Stack: My Journey with Kysely, Atlas, and Clerk](https://eliasson.me/articles/crafting-the-perfect-t3-stack-my-journey-with-kysely-atlas-and-clerk) - A blog post by [Johan Eliasson](https://twitter.com/elitasson) on how he built his [T3](https://create.t3.gg) inspired stack with [Kysely](https://kysely.dev), [Atlas](https://atlasgo.io/) and [Clerk](https://clerk.dev).
- [Build a fully typed web app using Next.js, PlanetScale, Drizzle, and Kysely](https://www.ayoubkhial.com/blog/build-fully-typed-web-app-using-next.js-planetscale-drizzle-and-kysely) - A blog post by [Ayoub Khial](https://twitter.com/ayoubkhial). If you're working with a [Next.js](https://nextjs.org) app based on TypeScript and searching for a reliable database solution, combining [PlanetScale](https://planetscale.com), [DrizzleORM](https://orm.drizzle.team), and [Kysely](https://kysely.dev) can be a mighty stack.
- [Kysely dialect for PlanetScale](https://depot.dev/blog/kysely-dialect-planetscale) - A blog post by [Jacob Gillespie](https://twitter.com/jacobwgillespie) on how [Depot](https://depot.dev) adopted [Kysely](https://kysely.dev) and [PlanetScale](https://planetscale.com/) and created the [Planetscale dialect](https://github.com/depot/kysely-planetscale).
- [Running Vercel Postgres Locally](https://gal.hagever.com/posts/running-vercel-postgres-locally) - A blog post by [Gal Schlezinger](https://twitter.com/galstar) on how he utilizes [neon](https://neon.tech)'s WebSockets proxy [docker](https://www.docker.com/) image and [Kysely](https://kysely.dev) to run his postgres queries locally and ship fast without breaking anything.
- [Simple CQRS in NodeJS with Typescript](https://itnext.io/simple-cqrs-in-nodejs-with-typescript-6da6d3e8a420) - A blog post by Illija on how to implement a simple CQRS pattern with query models using [Kysely](https://kysely.dev).
- [Kysely and CockroachDB](https://morgans-blog.deno.dev/kysely-crdb) - A blog post by [Morgan Winslow](https://github.com/mowinslow2) on [Kysely](https://kysely.dev) and how to use it with [CockroachDB](https://www.cockroachlabs.com).
- [Type-safe S3 Select queries with Kysely](https://dev.to/kumo/type-safe-s3-select-queries-with-kysely-4ge0) - A blog post by [Thomas Aribart](https://twitter.com/aribartt) on how to query [AWS S3](https://aws.amazon.com/s3) buckets, and how to do it in a type-safe manner with [Kysely](https://kysely.dev). Inspired the [S3 Select dialect](https://github.com/igalklebanov/kysely-s3-select).
- [Kysely: The Type-Safe SQL Query Builder for TypeScript](https://www.pugazhenthi.in/blog/kysely-typescript-sql-query-builder) - A blog post by [Pugazhenthi](https://github.com/codebypugazh) providing a short overview of [Kysely](https://kysely.dev).
- [Typescript で SQL を叩く方法を整理する](https://zenn.dev/moekidev/articles/d3db4dc362b93d) - A blog post by [moekidev](https://twitter.com/moekidev) about trying out [Kysely](https://kysely.dev) with [Prisma](https://www.prisma.io) and [Vercel Postgres](https://vercel.com/postgres).
- [現状Cloudflare WorkersでGraphQLサーバを構築するならコレ](https://zenn.dev/chimame/articles/3e7f0f0f7e783d) - A blog post by [chimame](https://twitter.com/chimame_rt) about combining [GraphQL](https://graphql.org/), [Prisma](https://www.prisma.io) and [Kysely](https://kysely.dev) on [Cloudflare Workers](https://workers.cloudflare.com).
- [Kysely が Knex をリプレイスする日も近いかもしれない](https://zenn.dev/acro5piano/articles/388b504289ccaa) - A blog post by [acro5piano](https://github.com/acro5piano) comparing the type safety of Kysely, Knex, and Slonik.

## CLIs

- [kysely-migrate](https://github.com/tmm/kysely-migrate) - [Kysely](https://kysely.dev) migrations and codegen CLI. ![npm](https://img.shields.io/npm/dw/kysely-migrate?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/tmm/kysely-migrate?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-migrate?style=flat-square)
- [kysely-migration-cli](https://github.com/acro5piano/kysely-migration-cli) - Thin migration cli library for [Kysely](https://kysely.dev). ![npm](https://img.shields.io/npm/dw/kysely-migration-cli?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/acro5piano/kysely-migration-cli?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-migration-cli?style=flat-square)

## Dialects

| name | description | url | status |
| :--- | :--- | :---: | :--- |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/a8476f18-1c4e-4d51-8b18-76d5fbbe1af6" alt="logo" width="24" height="24"/> kysely-data-api | This library adds [AWS RDS Data Api](https://docs.aws.amazon.com/rdsdataservice/latest/APIReference/Welcome.html) support for [Kysely](https://kysely.dev). <br/>It has support for both [MySQL](https://www.mysql.com) and [Postgres](https://www.postgresql.org). | [link](https://github.com/serverless-stack/kysely-data-api) | ![npm](https://img.shields.io/npm/dw/kysely-data-api?style=flat-square) <br/>![GitHub stars](https://img.shields.io/github/stars/serverless-stack/kysely-data-api?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/kysely-data-api?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/e3f07b5d-ec9f-4351-ac29-0bafa3da7902" alt="logo" width="24" height="24"/> kysely-postgres-js | [Kysely](https://kysely.dev) dialect for [PostgreSQL](https://www.postgresql.org) using the [Postgres.js](https://github.com/porsager/postgres) client library under the hood. <br/>This dialect should not be confused with [Kysely](https://kysely.dev)'s built-in [PostgreSQL](https://www.postgresql.org) dialect, <br/>which uses the [pg](https://github.com/brianc/node-postgres) client library instead. | [link](https://github.com/igalklebanov/kysely-postgres-js) | ![npm](https://img.shields.io/npm/dw/kysely-postgres-js?style=flat-square) <br/>![GitHub stars](https://img.shields.io/github/stars/igalklebanov/kysely-postgres-js?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/kysely-postgres-js?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/06f57eec-3ed4-4321-9709-e6effe24b015" height="24" width="24" /> kysely-planetscale | A [Kysely](https://kysely.dev) dialect for [PlanetScale](https://planetscale.com), <br/>using the [PlanetScale](https://planetscale.com) serverless driver for JavaScript. | [link](https://github.com/depot/kysely-planetscale) | ![npm](https://img.shields.io/npm/dw/kysely-planetscale?style=flat-square) <br/>![GitHub stars](https://img.shields.io/github/stars/depot/kysely-planetscale?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/kysely-planetscale?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/1c426e0d-ebc2-4eb7-9327-7a0a8336dced" height="24" width="24" /> @vercel/postgres-kysely | A [@vercel/postgres](https://github.com/vercel/storage/tree/main/packages/postgres) wrapper for the [Kysely](https://kysely.dev) query builder. | [link](https://github.com/vercel/storage/tree/main/packages/postgres-kysely) | ![npm](https://img.shields.io/npm/dw/@vercel/postgres-kysely?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/@vercel/postgres-kysely?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/a84b5258-0e09-46b7-9d8d-0efe8604dd97" height="24px" width="24px" /> kysely-neon | [Kysely](https://kysely.dev) dialect for [Neon](https://neon.tech) serverless [Postgres](https://www.postgresql.org). | [link](https://github.com/seveibar/kysely-neon) | ![npm](https://img.shields.io/npm/dw/kysely-neon?style=flat-square) <br/>![GitHub stars](https://img.shields.io/github/stars/seveibar/kysely-neon?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/kysely-neon?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/b9ae2b41-f642-4e06-9375-23ee726bc89f" height="24px" width="24px" /> @xata.io/kysely | A [Kysely](https://github.com/kysely-org/kysely) dialect for [Xata](https://xata.io), using the [Xata serverless driver for TypeScript](https://github.com/xataio/client-ts). | [link](https://github.com/xataio/client-ts/tree/main/packages/plugin-client-kysely) | ![npm](https://img.shields.io/npm/dw/@xata.io/kysely?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/@xata.io/kysely?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/d1546783-0d15-4a65-a6ba-00b604757159" height="24px" width="24px" /> kysely-d1 | [Kysely](https://kysely.dev) dialect for [Cloudflare D1](https://developers.cloudflare.com/d1). | [link](https://github.com/aidenwallis/kysely-d1) | ![npm](https://img.shields.io/npm/dw/kysely-d1?style=flat-square) <br/>![GitHub stars](https://img.shields.io/github/stars/aidenwallis/kysely-d1?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/kysely-d1?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/8636ebf2-9d68-4bf6-bf13-774605160c5d" height="24px" width="24px" /> kysely-bun-worker | [Kysely](https://kysely.dev) dialect for [Bun SQLite](https://bun.sh/docs/api/sqlite), run sql in worker. | [link](https://github.com/subframe7536/kysely-sqlite-tools/tree/master/packages/dialect-bun-worker) | ![npm](https://img.shields.io/npm/dw/kysely-bun-worker?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/kysely-bun-worker?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/5f68d6f4-321e-4374-bb5f-4034823c2d6f" height="24px" width="24px" /> @libsql/kysely-libsql | A [Kysely](https://kysely.dev) dialect for [libSQL/sqld](https://github.com/libsql/sqld), using the Hrana protocol over a WebSocket. | [link](https://github.com/libsql/kysely-libsql) | ![npm](https://img.shields.io/npm/dw/@libsql/kysely-libsql?style=flat-square) <br/>![GitHub stars](https://img.shields.io/github/stars/libsql/kysely-libsql?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/@libsql/kysely-libsql?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/4a87ec6b-f229-45de-91de-ad9de2e6b768" height="24px" width="24px" /> kysely-sqlite-worker | Execute SQL in [Node worker threads](https://nodejs.org/api/worker_threads.html), using [better-sqlite3](https://github.com/WiseLibs/better-sqlite3). | [link](https://github.com/subframe7536/kysely-sqlite-tools/tree/master/packages/dialect-sqlite-worker) | ![npm](https://img.shields.io/npm/dw/kysely-sqlite-worker?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/kysely-sqlite-worker?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/4a87ec6b-f229-45de-91de-ad9de2e6b768" height="24px" width="24px" /> kysely-wasm | [WebAssembly](https://webassembly.org) dialect for [Kysely](https://kysely.dev). | [link](https://github.com/subframe7536/kysely-sqlite-tools/tree/master/packages/dialect-wasm) | ![npm](https://img.shields.io/npm/dw/kysely-wasm?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/kysely-wasm?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/4a8c91e1-a52d-4687-989b-2a743c0142b5" height="24px" width="24px" /> kysely-dialect-tauri | [Kysely](https://kysely.dev) dialect using [Tauri](https://tauri.app)'s official [SQLite](https://www.sqlite.org/index.html) [plugin](https://github.com/tauri-apps/plugins-workspace/tree/dev/plugins/sql). | [link](https://github.com/subframe7536/kysely-sqlite-tools/tree/master/packages/dialect-tauri) | ![npm](https://img.shields.io/npm/dw/kysely-dialect-tauri?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/kysely-dialect-tauri?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/4a87ec6b-f229-45de-91de-ad9de2e6b768" height="24px" width="24px" /> kysely-wasqlite-worker | Execute SQL in [Web Worker](https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API/Using_web_workers), using [wa-sqlite](https://github.com/rhashimoto/wa-sqlite), store data in [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API). | [link](https://github.com/subframe7536/kysely-sqlite-tools/tree/master/packages/dialect-wasqlite-worker) | ![npm](https://img.shields.io/npm/dw/kysely-wasqlite-worker?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/kysely-wasqlite-worker?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/86b92c6f-2f84-448b-8ec8-f4106173b733" height="24px" width="24px" /> kysely-singlestore | [Kysely](https://kysely.dev) dialects, plugins and other goodies for [SingleStore](https://www.singlestore.com) (formerly MemSQL). | [link](https://github.com/igalklebanov/kysely-singlestore) | ![npm](https://img.shields.io/npm/dw/kysely-singlestore?style=flat-square) <br/>![GitHub stars](https://img.shields.io/github/stars/igalklebanov/kysely-singlestore?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/kysely-singlestore?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/6e9939f7-0605-4892-b991-04859dc21e99" height="24px" width="24px" /> kysely-surrealdb | [Kysely](https://kysely.dev) dialects, plugins and other goodies for [SurrealDB](https://surrealdb.com). <br/>SurrealQL is based on SQL, so why not? :trollface: | [link](https://github.com/igalklebanov/kysely-surrealdb) | ![npm](https://img.shields.io/npm/dw/kysely-surrealdb?style=flat-square) <br/>![GitHub stars](https://img.shields.io/github/stars/igalklebanov/kysely-surrealdb?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/kysely-surrealdb?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/32109eb8-42e1-4265-928b-71493b3544f1" height="24px" width="24px" /> @andersgee/kysely-fetch-driver | Edge compatible fetch driver for [Kysely](https://kysely.dev). | [link](https://github.com/Andersgee/kysely-fetch-driver) | ![npm](https://img.shields.io/npm/dw/@andersgee/kysely-fetch-driver?style=flat-square) <br/>![GitHub stars](https://img.shields.io/github/stars/Andersgee/kysely-fetch-driver?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/@andersgee/kysely-fetch-driver?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/369ad003-429b-4578-b0c5-d02c8c742d28" height="24px" width="24px" /> @tidbcloud/kysely | [Kysely](https://kysely.dev) dialect for [TiDB Cloud](https://tidbcloud.com), using the [TiDB Cloud serverless driver](https://github.com/tidbcloud/serverless-js). | [link](https://github.com/tidbcloud/kysely) | ![npm](https://img.shields.io/npm/dw/@tidbcloud/kysely?style=flat-square) <br/>![GitHub stars](https://img.shields.io/github/stars/tidbcloud/kysely?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/@tidbcloud/kysely?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/9a44e8a4-428b-4544-a071-93f32ca57ab2" height="24px" width="24px" /> kysely-s3-select | [Kysely](https://kysely.dev) dialects, plugins and other goodies for [Amazon S3 Select](https://docs.aws.amazon.com/AmazonS3/latest/userguide/selecting-content-from-objects.html). | [link](https://github.com/igalklebanov/kysely-s3-select) | ![npm](https://img.shields.io/npm/dw/kysely-s3-select?style=flat-square) <br/>![GitHub stars](https://img.shields.io/github/stars/igalklebanov/kysely-s3-select?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/kysely-s3-select?style=flat-square) |
| <img src="https://github.com/kysely-org/awesome-kysely/assets/14938291/d3baa062-1a6c-4c87-9aaf-625d26838680" height="24px" width="24px" /> kysely-duckdb | This dialect allows you to use [Kysely](https://kysely.dev) with [DuckDB](https://duckdb.org). | [link](https://github.com/runoshun/kysely-duckdb) | ![npm](https://img.shields.io/npm/dw/kysely-duckdb?style=flat-square) <br/>![GitHub stars](https://img.shields.io/github/stars/runoshun/kysely-duckdb?style=flat-square) <br/>![NPM](https://img.shields.io/npm/l/kysely-duckdb?style=flat-square) |

## ORMs

- [kysely-orm](https://github.com/seeden/kysely-orm) - TypeSafe ORM for [Kysely](https://kysely.dev) library. ![npm](https://img.shields.io/npm/dw/kysely-orm?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/seeden/kysely-orm?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-orm?style=flat-square)
- [kysely-mapper](https://github.com/jtlapp/kysely-mapper) - Flexible [Kysely](https://kysely.dev)-based utility for mapping between tables and objects. ![npm](https://img.shields.io/npm/dw/kysely-mapper?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/jtlapp/kysely-mapper?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-mapper?style=flat-square)

## Plugins

- [kysely-plugin-serialize](https://github.com/subframe7536/kysely-sqlite-tools/tree/master/packages/plugin-serialize) - [Kysely](https://kysely.dev) plugin that serializes parameters. ![npm](https://img.shields.io/npm/dw/kysely-plugin-serialize?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-plugin-serialize?style=flat-square)
- [kysely-access-control](https://github.com/ben-pr-p/kysely-utils/tree/main/packages/kysely-access-control) - plugin that allows you to Allow/Deny/Omit (or add a where clause) to access any kysely table or column
- [kysely-grants](https://github.com/ben-pr-p/kysely-utils/tree/main/packages/kysely-grants) - plugin that implements "Postgres-style grants" on top of [kysely-access-control](https://github.com/ben-pr-p/kysely-utils/tree/main/packages/kysely-access-control)
- [kysely-plugin-prefix](https://github.com/cloudmix-dev/kysely-plugin-prefix) - set of plugins that allow you to prefix table and index names implicitly

## Templates

- [Acme Corp](https://acme-corp.jumr.dev) - Your all-in-one, enterprise ready starting point. Full-stack Typesafety with [tRPC](https://trpc.io/), [Next.js](https://nextjs.org), and [React](https://react.dev) Server Components. Typesafe database access using [Kysely](https://kysely.dev) as a query builder, and [Prisma](https://www.prisma.io) for schema management. ![GitHub stars](https://img.shields.io/github/stars/juliusmarminge/acme-corp?style=flat-square) ![GitHub](https://img.shields.io/github/license/juliusmarminge/acme-corp?style=flat-square)
- [create-o7-app](https://github.com/ottomated/create-o7-app) - An opinionated CLI for creating type-safe [Svelte](https://svelte.dev) apps. create-o7-app's template includes [Kysely](https://kysely.dev) for Edge support and fast cold starts, with all the convenience of using [Prisma](https://www.prisma.io) to define your database model. ![npm](https://img.shields.io/npm/dw/create-o7-app?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/ottomated/create-o7-app?style=flat-square) ![NPM](https://img.shields.io/npm/l/create-o7-app?style=flat-square)
- [remix-d1-kysely-demo](https://github.com/niconiahi/remix-d1-kysely-demo) - In this repo you'll learn how to setup a [D1](https://developers.cloudflare.com/d1) database starting from [Remix](https://remix.run)'s [@cloudflare/pages](https://pages.cloudflare.com) template and how to interact with it using [Kysely](https://kysely.dev) query builder. ![GitHub stars](https://img.shields.io/github/stars/niconiahi/remix-d1-kysely-demo?style=flat-square) ![GitHub](https://img.shields.io/github/license/niconiahi/remix-d1-kysely-demo?style=flat-square)
- [Vercel Postgres + Kysely Next.js Starter](https://vercel.com/templates/next.js/postgres-kysely) - Simple [Next.js](https://nextjs.org) template that uses [Vercel Postgres](https://vercel.com/postgres) as the database and [Kysely](https://kysely.dev) as the query builder.

## Tools

- [kysely-playground](https://kyse.link) - Playground for [Kysely](https://kysely.dev). Provides vscode-like experiences including type checking and auto suggestions. Supports built-in dialects ([Postgres](https://postgresql.org), [MySQL](https://www.mysql.com), [SQLite](https://sqlite.org)), last 20 [Kysely](https://kysely.dev) versions. You can test stuff quickly, and create issues with reproducing with the playground. ![GitHub stars](https://img.shields.io/github/stars/wirekang/kysely-playground?style=flat-square)
- [Kysely Assistant](https://chat.openai.com/g/g-656EWqn2W-kysely-assistant) - Translate SQL to [Kysely](https://kysely.dev) syntax using [Chat GPT](https://chat.openai.com).

## Type Generators

- [kysely-codegen](https://github.com/RobinBlomberg/kysely-codegen) - Generate [Kysely](https://kysely.dev) type definitions from your database. ![npm](https://img.shields.io/npm/dw/kysely-codegen?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/RobinBlomberg/kysely-codegen?style=flat-square) ![GitHub](https://img.shields.io/github/license/RobinBlomberg/kysely-codegen?style=flat-square)
- [prisma-kysely](https://github.com/valtyr/prisma-kysely) - Generate [Kysely](https://kysely.dev) types directly from your [Prisma](https://www.prisma.io) schema. ![npm](https://img.shields.io/npm/dw/prisma-kysely?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/valtyr/prisma-kysely?style=flat-square) ![NPM](https://img.shields.io/npm/l/prisma-kysely?style=flat-square)
- [kanel-kysely](https://github.com/kristiandupont/kanel/tree/main/packages/kanel-kysely) - Generate [Kysely](https://kysely.dev) types directly from your [PostgreSQL](https://www.postgresql.org) database. This package extends [Kanel](https://github.com/kristiandupont/kanel) with some [Kysely](https://kysely.dev) specific features. ![npm](https://img.shields.io/npm/dw/kanel-kysely?style=flat-square) ![NPM](https://img.shields.io/npm/l/kanel-kysely?style=flat-square)

## Videos

- [I tried 8 different Postgres ORMs](https://youtu.be/4QN1BzxF8wM) - [Fireship](https://twitter.com/fireship_dev) breaks down some popular [PostgreSQL](https://www.postgresql.org) libraries in the [Node.js](https://nodejs.org) ecosystem. Starting from client libraries, going through query builders ([Kysely](https://kysely.dev) is mentioned starting at the [5:20](https://youtu.be/4QN1BzxF8wM?t=320) mark) and then finishing with ORMs.
- [Kysely first impressions - Typescript SQL query builder and migrations](https://www.youtube.com/watch?v=vnSnor_C2rA) - In the video we take a quick look at a new Typescript SQL query builder which optimizes for type-safety and the best possible intellisense. We'll walk through how to use it to connect to a database and perform typical CRUD queries, we'll explore how to simulate relational queries, and finally, we'll give their migration feature a try!
- [We need to talk about Prisma](https://youtu.be/J2j1XwZRi30) - [Mehul Mohan](https://twitter.com/mehulmpt) talks about what [codedamn](https://codedamn.com) went through while migrating from [MongoDB](https://mongodb.com) to [Prisma](https://prisma.io) and [Planetscale](https://planetscale.com), and their eventual re-re-write to [AWS Aurora](https://aws.amazon.com/rds/aurora) and [Kysely](https://kysely.dev) for type-safety and performance (starts at the [14:37](https://youtu.be/J2j1XwZRi30?t=877) mark).
- [Let's Talk About Database Performance](https://youtu.be/3P7jnolWfHw) - [Theo Browne aka t3.gg](https://twitter.com/t3dotgg) talks about database performance, [Prisma](https://www.prisma.io), serverless and edge functions, [PlanetScale](https://planetscale.com), their Data API offering and type-safety via [Kysely](https://kysely.dev) (starts at the [15:57](https://youtu.be/3P7jnolWfHw?t=957) mark).
- [Type-Safe SQL on the Edge with Kysely](https://youtu.be/zd9a_Lk3jAc) - [Supabase](https://supabase.com) Edge Functions can connect directly to your [Postgres](https://www.postgresql.org) database to execute SQL Queries. [Kysely](https://kysely.dev) is a type-safe and autocompletion-friendly typescript SQL query builder. Combining [Kysely](https://kysely.dev) with [Deno Postgres](https://deno-postgres.com) provides a neat developer experience for interacting directly with your [Postgres](https://www.postgresql.org) database.
- [2022-08-12 - Fresh Spots - Deno + Fresh Part 4 - Kysely DB Setup / Replacement](https://www.youtube.com/watch?v=C14LWU6zJvA) - Watch [Coding Garden](https://twitter.com/coding_garden) as he combines [Kysely](https://kysely.dev) (starts at the [12:09](https://www.youtube.com/watch?v=C14LWU6zJvA&t=729s) mark), [Deno](https://deno.com/runtime) and [Fresh](https://fresh.deno.dev) on his stream.
- [how to get better at typescript (feat. kysely)](https://youtu.be/8yZtpRyYiRM) - While videos and blog posts are great, nothing teaches me faster than trying to duplicate a cool pattern or technique. Sometimes that pattern comes from other languages, like Rust, and sometimes, it's something that TS developers who are way smarter than me have come up with.
