# Hi, I'm Aman 👋

> Tinkerer, builder, product-minded engineer.

I like building things end to end. A lot of my work is in Go on backend infrastructure: caching, distributed locking, error handling, code generation. I also build AI coding tools, GraphQL tooling, Chrome extensions, and the occasional full product when an idea grabs me.

I open-source most of what I make, spend my days in the terminal on Linux, and speak when I get the chance. There are 100+ public repos on here by now, across infrastructure, AI tooling, and small utilities I built to fix my own annoyances.

[![Website](https://img.shields.io/badge/Website-khanakia.com-FF5722?style=flat-square&logo=googlechrome&logoColor=white)](https://khanakia.com)
[![X](https://img.shields.io/badge/Follow-@amankhanakia-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/amankhanakia)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-khanakia-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/khanakia/)
![Profile views](https://komarev.com/ghpvc/?username=khanakia&style=flat-square&color=00ADD8&label=Profile+views)

## 🎩 What I do

- 🔧 **Tinkerer.** If something annoys me, I build a tool for it. Half my repos started that way.
- 🏗️ **Infrastructure engineer.** Caching, distributed locking, error handling, codegen. The layer that decides whether a product holds up at scale.
- 🤖 **AI tooling builder.** Local-first tools that make coding agents (and the people using them) faster.
- 📦 **Product person.** I care whether a real user wants the thing, not just whether the code is clever.
- 🎤 **Consultant and speaker.** I help teams ship and talk shop when I can.

## 🧱 Stack

![Stack](https://skillicons.dev/icons?i=go,ts,js,graphql,postgres,redis,sqlite,docker,react,nextjs,nodejs,tailwind,linux&perline=14)

Also daily: **Ent ORM** · **gqlgen** · **TanStack** · **OpenTelemetry** · **PKL** · **Chrome Extensions** · **MCP** · **NATS**

## 🚀 Start here

A few worth a look:

- 🔀 **[vercelgate](https://github.com/khanakia/vercelgate)** `⭐ 22`: switch between multiple Vercel accounts from the CLI.
- 🧬 **[gqlkit](https://github.com/khanakia/gqlkit)** `⭐ 6`: typed GraphQL client SDKs for Go and TypeScript with a builder API, so you stop hand-writing queries.
- 🧩 **[entx](https://github.com/khanakia/entx)** `⭐ 5`: Ent ORM extensions for polymorphic relationships and GraphQL schema splitting.
- 📐 **[sql-schema-visualizer](https://github.com/khanakia/sql-schema-visualizer)**: paste PostgreSQL/MySQL/SQLite DDL, see your schema. Free and runs fully in the browser.
- 🧠 **[lore](https://github.com/thesatellite-ai/lore)**: local-first knowledge and context store for AI coding agents (and humans).
- 📄 **[filemark](https://github.com/thesatellite-ai/filemark)**: Chrome extension that renders Markdown, MDX, JSON, SQL, Prisma and DBML.

## 🏗️ What I'm building

My work lives in three places, depending on what you need.

### ⚙️ Go backend infrastructure: [@ubgo](https://github.com/ubgo)

Go libraries for the lower-level, production-critical stuff.

- 🔒 **[lock](https://github.com/ubgo/lock)**: distributed locking over Redis, Postgres and etcd behind one interface.
- 🗃️ **[cache](https://github.com/ubgo/cache)**: generics-based, tiered and distributed caching (plus `cache-cli`, `cache-tiered`, `threadsafecache`).
- ⚠️ **[errx](https://github.com/ubgo/errx)**: structured error handling with diagnostics.
- 📋 **[logger](https://github.com/ubgo/logger)**: pluggable, adapter-based logging.
- 🧰 **[gqlutil](https://github.com/ubgo/gqlutil)** / **[gqlmodel](https://github.com/ubgo/gqlmodel)**: gqlgen helpers and custom scalars.
- 🆔 **[gormuuid](https://github.com/ubgo/gormuuid)**: Postgres `uuid[]` fields for GORM.

### 🤖 AI coding tooling: [@thesatellite-ai](https://github.com/thesatellite-ai)

Local-first tools for AI coding agents and the people using them.

- 🧠 **[lore](https://github.com/thesatellite-ai/lore)**: knowledge and context store for AI agents.
- 📄 **[filemark](https://github.com/thesatellite-ai/filemark)**: Markdown/MDX/SQL/Prisma renderer extension.
- 🌐 **[fetchr](https://github.com/thesatellite-ai/fetchr)**: HTTP client with TLS fingerprinting (JA3/JA4, HTTP/2). CLI, MCP server and Go package.
- 🔗 **[repolink](https://github.com/thesatellite-ai/repolink)**: symlink shared folders across repos (Go + Ent + SQLite).
- 🧩 **[codeskill](https://github.com/thesatellite-ai/codeskill)**: AI project intelligence with tiered rules, switchable behaviours and iterative learning.

### 🧰 Standalone tools and generators: [@khanakia](https://github.com/khanakia?tab=repositories)

- 🔁 **[gots](https://github.com/khanakia/gots)**: Go to TypeScript generator for types, enums and consts.
- 🔍 **[http-lens](https://github.com/khanakia/http-lens)**: debug HTTP/GraphQL requests inside Chrome DevTools.
- 🚀 **[boilerplate-golang](https://github.com/khanakia/boilerplate-golang)**: Ent + GraphQL + PKL + NATS + OpenTelemetry starter.
- ⚡ **[boilerplate-tanstack](https://github.com/khanakia/boilerplate-tanstack)**: full-stack TanStack Start starter.

## 📊 By the numbers

![Stats](https://github-readme-stats.vercel.app/api?username=khanakia&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true&title_color=00ADD8&icon_color=7B42BC)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=khanakia&layout=compact&theme=tokyonight&hide_border=true&title_color=00ADD8&langs_count=10)

## 🧭 How I work

I'd rather ship something small and useful than sit on a perfect version forever. I try a lot of ideas and keep the ones that work. Most of it goes open-source so other people can build on it. And I spend more time than most on the parts nobody brags about, like caching and codegen, because that's usually what breaks first.

---

⭐ If any of these saved you time, a star helps others find them. More at [**khanakia.com**](https://khanakia.com/). Got an idea or want to build something? Say hi on [𝕏 @amankhanakia](https://x.com/amankhanakia).
