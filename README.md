<div align="center">

<img src="./header.svg" alt="Hello! I'm Leon — Backend / Full-stack developer" />

**Backend-leaning full-stack developer, in commercial development since 2021**  
TypeScript · NestJS · Python · PostgreSQL · Docker

[Portfolio](https://leonsnow.is-a.dev) · [Telegram](https://t.me/Le47on)

</div>

---

### Experience

| When | What | Stack |
|:-----|:-----|:------|
| 2026 | **[Nodefy](https://nodefy.pro)** — visual workflow platform, primary developer | NestJS, BullMQ, Prisma, React |
| 2026 | **Cosmetics store** — replatforming from WordPress, sole developer | NestJS, Prisma, Next.js |
| 2026 | **[Creon](https://creon-cg.com)** — agency website, team project | React, Express, Strapi |
| 2025–2026 | **Ural Mining Company** — about 40 company websites | Laravel, Nuxt, Filament |
| 2023 | **[KUB8 Academy](https://kub-8.com/academy/)** — personalized learning paths | Laravel, Vue |
| 2022 | **[Talk to Loop](https://minorityrights.org/talk-to-loop/)** (Minority Rights Group) — anonymous multilingual feedback platform | Angular, Node.js, Twilio, AWS |
| 2021–2022 | Frontend developer — first commercial role | |

---

### Selected work

#### [Nodefy](https://nodefy.pro) — visual workflow platform

About 90% of 500+ commits are mine, from the schema and queues to the node editor. 50 Prisma migrations, 470+ test cases.

- Concurrent runs: `pg_advisory_xact_lock` on run creation and graph mutation, capped active runs per node, deterministic BullMQ job ids
- Billing: signed payment webhooks with constant-time HMAC checks, token spending under `FOR UPDATE`

#### Cosmetics store — production e-commerce

Moved a live WooCommerce store to NestJS + Next.js, alone: 39 models, 5 containers on a VPS.

- Migration tooling: 36 scripts for classic and HPOS orders, with comparison and sampling checks; legacy phpass passwords keep working
- Payments: YooKassa and Dolyame webhooks, payment state re-fetched from the provider, fiscal receipts
- Reliability: post-payment retry queue in PostgreSQL, unique per order and task, with capped exponential backoff
- MoySklad sync for products, stock and orders

#### Pchelka-CRM — studio CRM *(private)*

NestJS, BullMQ, socket.io and Prisma monorepo. Secrets encrypted with AES-256-GCM, e2e coverage of the critical flow, CI.

#### TraceDock — observability pet project *(private)*

8 NestJS services over RabbitMQ and ClickHouse: batched ingest, dead-letter queue, alerts to Slack, Telegram, Discord and email.

---

### Public code

| Project | What it shows | Stack |
|:--------|:--------------|:------|
| **[Pchelka](https://github.com/Lleonsnow/Pchelka)** | Telegram shop: bot and Mini App on one database, initData HMAC validation | Aiogram 3, Django, Next.js |
| **[Couponator](https://github.com/Lleonsnow/Couponator)** | Coupon platform with Admitad feed sync | Next.js, Prisma, PostgreSQL |
| **[banking-system](https://github.com/Lleonsnow/banking-system)** | Double-entry transfers and exchange, ordered row locks, reconciliation endpoint | NestJS, TypeORM, React |
| **[credit-risk-summary](https://github.com/Lleonsnow/credit-risk-summary)** | Risk summary on synthetic data: SQL invariants, independent recalculation in `Decimal` | PostgreSQL, Python, Vega-Lite |
| **[file-exchange-task](https://github.com/Lleonsnow/file-exchange-task)** | Test assignment: layered API, Celery pipeline, strict mypy, Locust | FastAPI, Celery, Next.js |

---

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,nestjs,python,fastapi,django,laravel,postgres,redis,docker,nginx,nextjs,react,vue&perline=13" alt="TypeScript, NestJS, Python, FastAPI, Django, Laravel, PostgreSQL, Redis, Docker, Nginx, Next.js, React, Vue" />

<br /><br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./icons/github-snake.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./icons/github-snake-light.svg" />
  <img alt="GitHub contribution snake" src="./icons/github-snake.svg" />
</picture>

**Open to backend / full-stack roles** · [Telegram @Le47on](https://t.me/Le47on)

</div>
