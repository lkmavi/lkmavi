# Hi there, I'm Vladimir 👋

Backend engineer focused on Go. I build reliable microservices, event-driven systems, and developer tooling.

---

### Tech

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

---

## What I've worked on

5 years in backend. Mostly Go — microservices, event-driven pipelines, payment integrations, search.

Some things I've built or owned along the way:

- **Cart & checkout decomposition** — designed the service boundary and API contract, implemented saga orchestration for order flow, handled compensation steps for payment and warehouse failures. Solved atomicity with optimistic locking and idempotent operations.
- **Kafka event pipelines** — end-to-end logistics flow across production, planning, and delivery services. Versioned events, replay mechanisms, partial batch and redelivery edge cases.
- **SQL performance** — slow query audits, eliminated N+1 and unnecessary joins, composite indexes, table partitioning for high-volume tables. Used EXPLAIN throughout.
- **Elasticsearch** — product catalog indexing, facets, relevance tuning, bulk indexing for updates, replication for availability.
- **Payment integrations** — Stripe, PayPal, YooKassa, Tinkoff and others. Partial refunds, fund distribution between marketplace and sellers, retry and rollback strategies.
- **Delivery module** — aggregated multiple courier APIs, picked optimal route by cost and SLA, status tracking with retry logic for flaky external services.
- **Observability** — centralized log stack (Loki + Grafana), metrics with Prometheus, standardized log format across services.

---

## Projects

| | |
|---|---|
| **[slogx](https://github.com/salivare-io/slogx)** | runtime-configurable wrapper around stdlib `slog` ([salivare-io](https://github.com/salivare-io)) |
| **[gopriv](https://github.com/salivare-io/gopriv)** | CLI tool for working with private Go repositories |
| **[sso-auth-server](https://github.com/salivare-io/sso-auth-server/tree/dev)** | SSO with Google / Yandex providers (WIP) |
| **[geckty](https://github.com/geckty/geckty)** | GUI terminal on [gogpu](https://github.com/gogpu/gogpu) — kitty/Rio/Alacritty spirit, glass chrome, tabs & plugins (WIP) |

---

## GoGPU Ecosystem

Contributor to the [GoGPU](https://github.com/gogpu) ecosystem — Pure Go GPU computing stack, zero CGO, cross-platform.

| Package | What I worked on |
|---|---|
| **[gogpu](https://github.com/gogpu/gogpu)** | windowing & menus (live resize, multi-window, native menus), strided damage uploads & GPU stats ([#484](https://github.com/gogpu/gogpu/issues/484)) |
| **[wgpu](https://github.com/gogpu/wgpu)** | Metal live-resize IOSurface pool fixes, GLES stability |
| **[gg](https://github.com/gogpu/gg)** | raster & stencil rendering fixes |
| **[gpucontext](https://github.com/gogpu/gpucontext)** | strided `TextureRegionUpdater.UpdateRegion` |

Issues & features: [#206](https://github.com/gogpu/gogpu/issues/206) · [#213](https://github.com/gogpu/gogpu/issues/213) · [#223](https://github.com/gogpu/gogpu/issues/223) · [#242](https://github.com/gogpu/gogpu/issues/242) · [#264](https://github.com/gogpu/gogpu/issues/264) · [#484](https://github.com/gogpu/gogpu/issues/484)

---

## Contacts

[![Telegram](https://img.shields.io/badge/@zvladimir__769-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](https://t.me/zvladimir_769)
