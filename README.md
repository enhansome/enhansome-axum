# Awesome axum with stars

[axum](https://crates.io/crates/axum) is an HTTP routing and request-handling library written in Rust that focuses on ergonomics and modularity.
[repository](https://github.com/tokio-rs/axum) ⭐ 26,978 | 🐛 77 | 🌐 Rust | 📅 2026-08-28

This page contains a list of axum-related crates, project showcases, tutorials, videos, and other assorted items.

It started as a copy of the `ECOSYSTEM.md` file of the [repository of axum](https://github.com/tokio-rs/axum) ⭐ 26,978 | 🐛 77 | 🌐 Rust | 📅 2026-08-28 when it was [removed](https://github.com/tokio-rs/axum/pull/3737) ⭐ 26,978 | 🐛 77 | 🌐 Rust | 📅 2026-08-28. After a brief maintenance as part of the 📖 [Code Maven axum book](https://axum.code-maven.com/) it was moved to the 🎉 [awesome axum](https://github.com/szabgab/awesome-axum) ⭐ 108 | 🐛 0 | 📅 2026-05-07 repository.

## Contribution

If your project isn't listed here and you would like it to be, please feel free to create a PR.

If you find a broken link or incorrect information, please feel free to open an issue or create a PR.

## Disclaimer

I have not checked these projects and I don't necessarily recommend them. Use them at your own discretion.

## 📦 Community maintained axum ecosystem

* [loco.rs](https://github.com/loco-rs/loco) ⭐ 9,102 | 🐛 15 | 🌐 Rust | 📅 2026-08-19: A full stack Web and API productivity framework similar to Rails, based on axum.
* [socketioxide](https://github.com/totodore/socketioxide) ⭐ 1,623 | 🐛 13 | 🌐 Rust | 📅 2026-08-24: An easy to use socket.io server implementation working as a `tower` layer/service.
* [zino](https://github.com/zino-rs/zino) ⭐ 1,145 | 🐛 8 | 🌐 Rust | 📅 2026-08-28: Zino is a next-generation framework for composable applications which provides full integrations with axum.
* [spring-rs](https://github.com/spring-rs/spring-rs) ⭐ 997 | 🐛 25 | 🌐 Rust | 📅 2026-08-28: spring-rs is a microservice framework written in rust inspired by java's spring-boot, based on axum
* [tower-sessions](https://github.com/maxcountryman/tower-sessions) ⭐ 422 | 🐛 3 | 🌐 Rust | 📅 2026-08-05: Sessions as a `tower` and `axum` middleware.
* [axum-htmx](https://github.com/robertwayne/axum-htmx) ⭐ 272 | 🐛 10 | 🌐 Rust | 📅 2026-01-20: Htmx extractors and request guards for axum.
* [ezsockets](https://github.com/gbaranski/ezsockets) ⭐ 265 | 🐛 13 | 🌐 Rust | 📅 2026-05-18: Easy to use WebSocket library that integrates with axum.
* [axum\_session](https://github.com/AscendingCreations/AxumSessions) ⭐ 204 | 🐛 3 | 🌐 Rust | 📅 2026-08-10: Database persistent sessions like pythons flask\_sessionstore for axum.
* [svelte-axum-project](https://github.com/jbertovic/svelte-axum-project) ⭐ 171 | 🐛 1 | 🌐 Rust | 📅 2023-10-17: Template and example for Svelte frontend app with axum as backend
* [axum-valid](https://github.com/gengteng/axum-valid) ⭐ 165 | 🐛 7 | 🌐 Rust | 📅 2026-06-30: Extractors for data validation using validator, garde, and validify.
* [axum\_session\_auth](https://github.com/AscendingCreations/AxumSessionsAuth) ⭐ 135 | 🐛 1 | 🌐 Rust | 📅 2026-08-10: Persistent session based user login with rights management for axum.
* [tower-resilience](https://github.com/joshrotenberg/tower-resilience) ⭐ 102 | 🐛 0 | 🌐 Rust | 📅 2026-08-23: Resilience middleware for tower: circuit breaker, bulkhead, retry, rate limiter, and more.
* [AxumKit](https://github.com/levish0/AxumKit) ⭐ 97 | 🐛 15 | 🌐 Rust | 📅 2026-08-02: Production-ready Rust web backend template with authentication, sea-orm (Postgres), SMTP email, Rate limiting with Redis, and deployment.
* [axum-template](https://github.com/Altair-Bueno/axum-template) ⭐ 96 | 🐛 2 | 🌐 Rust | 📅 2026-04-13: Layers, extractors and template engine wrappers for axum based Web MVC applications
* [axum-prometheus](https://github.com/ptrskay3/axum-prometheus) ⭐ 91 | 🐛 10 | 🌐 Rust | 📅 2026-07-31: A middleware library to collect HTTP metrics for axum applications, compatible with all [metrics.rs](https://metrics.rs) exporters.
* [axum-streams](https://github.com/abdolence/axum-streams-rs) ⭐ 88 | 🐛 1 | 🌐 Rust | 📅 2026-08-24: Streaming HTTP body with different formats: JSON, CSV, Protobuf.
* [axum-casbin-auth](https://github.com/casbin-rs/axum-casbin-auth) ⭐ 72 | 🐛 1 | 🌐 Rust | 📅 2026-05-15: Casbin access control middleware for axum
* [axum-template](https://github.com/janos-r/axum-template) ⭐ 69 | 🐛 0 | 🌐 Rust | 📅 2025-02-20: GraphQL and REST API, SurrealDb, JWT auth, direct error handling, request logs
* [axum-keycloak-auth](https://github.com/lpotthast/axum-keycloak-auth) ⭐ 66 | 🐛 17 | 🌐 Rust | 📅 2026-08-18: Protect axum routes with a JWT emitted by Keycloak.
* [rust-axum-with-google-oauth](https://github.com/randommm/rust-axum-with-google-oauth) ⭐ 53 | 🐛 0 | 🌐 Rust | 📅 2026-02-14: website template for Google OAuth authentication on axum, using SQLite with SQLx or MongoDB and MiniJinja.
* [axum-messages](https://github.com/maxcountryman/axum-messages) ⭐ 48 | 🐛 2 | 🌐 Rust | 📅 2025-01-01: One-time notification messages for axum.
* [seamjs](https://github.com/canmi21/seam) ⭐ 40 | 🐛 1 | 🌐 TypeScript | 📅 2026-07-03: Compile-time rendering framework where UI Stack (e.g. React...) pages are pre-rendered at build time and Axum serves them via Rust-native HTML slot injection (\~1ms/page), with typed RPC procedures codegen'd from a shared manifest. (Added on 2026.04.27)
* [axum-otel-metrics](https://github.com/ttys3/axum-otel-metrics/) ⭐ 39 | 🐛 1 | 🌐 Rust | 📅 2026-07-12: A axum OpenTelemetry Metrics middleware with prometheus exporter supported.
* [axum-restful](https://github.com/gongzhengyang/axum-restful) ⭐ 32 | 🐛 0 | 🌐 Rust | 📅 2023-12-19: A restful framework based on axum and sea-orm, inspired by django-rest-framework.
* [axum-tungstenite](https://github.com/davidpdrsn/axum-tungstenite) ⭐ 25 | 🐛 6 | 🌐 Rust | 📅 2024-03-16: WebSocket connections for axum directly using tungstenite
* [axum-helmet](https://github.com/danielkov/rust-helmet) ⭐ 22 | 🐛 0 | 🌐 Rust | 📅 2026-08-01: A security middleware library for popular Rust web frameworks, with first-class `axum` support. (Add on 2026.04.27)
* [axum-jrpc](https://github.com/0xdeafbeef/axum-jrpc) ⭐ 21 | 🐛 1 | 🌐 Rust | 📅 2026-01-07: Json-rpc extractor for axum
* [api-error](https://github.com/centreon/rs-api-error) ⭐ 18 | 🐛 1 | 🌐 Rust | 📅 2026-08-27: A proc macro to define HTTP errors in a thiserror way. It automatically implements `IntoResponse` for your error types. Allowing you to directly return `Result<(), MyError` from your axum handlers.
* [tower-otel](https://github.com/mattiapenati/tower-otel) ⭐ 13 | 🐛 8 | 🌐 Rust | 📅 2026-06-22: OpenTelemetry layer for HTTP/gRPC services with optional axum integration.
* [axum-serde](https://github.com/gengteng/axum-serde) ⭐ 12 | 🐛 0 | 🌐 Rust | 📅 2026-04-18: Provides multiple serde-based extractors / responses, also offers a macro to easily customize serde-based extractors / responses.
* [axum-rails-cookie](https://github.com/endoze/axum-rails-cookie) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2026-07-20: Extract rails session cookies in axum based apps.
* [baxe](https://github.com/zyphelabs/baxe) ⭐ 5 | 🐛 3 | 🌐 Rust | 📅 2026-07-09: Simple macro for defining backend errors once and automatically generate standardized JSON error responses, saving time and reducing complexity
* [axum-governor](https://crates.io/crates/axum-governor): An independent Axum middleware for rate limiting, powered by [lazy-limit](https://github.com/canmi21/lazy-limit) ⚠️ Archived (not related to tower-governor).
* [Feature Flag Service](https://github.com/webrowse/feature-flag-service-backend/) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-08-19: A production-ready feature flag management service built with Rust, Axum, and PostgreSQL. (Addedon 2026.04.27)
* [axum-ws-broadcaster](https://github.com/Necoo33/axum-ws-broadcaster) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2025-06-11: A broadcasting liblary for both [axum-typed-websockets](https://crates.io/crates/axum-typed-websockets) and `axum::extract::ws`.
* [axum-negotiate-layer](https://github.com/2ndDerivative/axum-negotiate-layer) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-05-10: Middleware/Layer for Kerberos/NTLM "Negotiate" authentication.
* [sigterm](https://github.com/canmi21/sigterm) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-01-27: Signal-aware async control and cancellation primitives for Tokio.
* [axum-server](https://crates.io/crates/axum-server): axum-server is a hyper server implementation designed to be used with axum.
* [axum-typed-websockets](https://crates.io/crates/axum-typed-websockets): `axum::extract::ws` with type safe messages.
* [tower-cookies](https://crates.io/crates/tower-cookies): Cookie manager middleware
* [axum-flash](https://crates.io/crates/axum-flash): One-time notifications (aka flash messages) for axum.
* [axum-msgpack](https://crates.io/crates/axum-msgpack): MessagePack Extractors for axum.
* [axum-sqlx-tx](https://crates.io/crates/axum-sqlx-tx): Request-bound [SQLx](https://crates.io/crates/sqlx) transactions with automatic commit/rollback based on response.
* [aliri\_axum](https://crates.io/crates/aliri_axum) and [aliri\_tower](https://crates.io/crates/aliri_tower): JWT validation middleware and OAuth2 scopes enforcing extractors.
* [axum-auth](https://crates.io/crates/axum-auth): High-level http auth extractors for axum.
* [axum-tracing-opentelemetry](https://crates.io/crates/axum-tracing-opentelemetry): Middlewares and tools to integrate axum + tracing + opentelemetry
* [aide](https://docs.rs/aide): Code-first Open API documentation generator with [axum integration](https://docs.rs/aide/latest/aide/axum/index.html).
* [axum-typed-routing](https://docs.rs/axum-typed-routing/latest/axum_typed_routing/): Statically typed routing macros with OpenAPI generation using aide.
* [rovo](https://docs.rs/rovo): Doc-comment-driven OpenAPI documentation generation for Axum web applications, built on top of aide.
* [axum-jsonschema](https://docs.rs/axum-jsonschema/): A `Json<T>` extractor that does JSON schema validation of requests.
* [axum-login](https://docs.rs/axum-login): Session-based user authentication for axum.
* [axum-gate](https://docs.rs/axum-gate): JWT-based authentication and role-based authorization for axum (Cookie and Bearer, for monolithic and distributed applications).
* [axum-csrf-sync-pattern](https://crates.io/crates/axum-csrf-sync-pattern): A middleware implementing CSRF STP for AJAX backends and API endpoints.
* [jwt-authorizer](https://crates.io/crates/jwt-authorizer): JWT authorization layer for axum (oidc discovery, validation options, claims extraction, etc.)
* [axum-typed-multipart](https://crates.io/crates/axum_typed_multipart): Type safe wrapper for `axum::extract::Multipart`.
* [tower-governor](https://crates.io/crates/tower_governor): A Tower service and layer that provides a rate-limiting backend by [governor](https://crates.io/crates/governor)
* [springtime-web-axum](https://crates.io/crates/springtime-web-axum): A web framework built on Springtime and axum, leveraging dependency injection for easy app development.
* [axum-test](https://crates.io/crates/axum-test): High level library for writing Cargo tests that run against axum.
* [tower\_allowed\_hosts](https://crates.io/crates/tower_allowed_hosts): Allowed hosts middleware which limits request from only allowed hosts.
* [axum-html-minifier](https://crates.io/crates/axum_html_minifier): This middleware minify the html body content of a axum response.
* [static-serve](https://crates.io/crates/static-serve): A helper macro for compressing and embedding static assets in an axum webserver.
* [datastar](https://crates.io/crates/datastar): Rust implementation of the Datastar SDK specification with Axum support
* [axum-conditional-requests](https://crates.io/crates/axum-conditional-requests): A library for handling client-side caching HTTP headers

## 🖼️ Projects with live deployed service

Probably the best way to learn how to use axum is by looking at projects that are providing service.

* [crates.io](https://crates.io/) itself uses axum as a web library and [diesel](https://crates.io/crates/diesel) for database access.  [GitHub](https://github.com/rust-lang/crates.io/) ⭐ 3,687 | 🐛 111 | 🌐 Rust | 📅 2026-08-28  (axum 0.8.9)

## 🖼️ Project showcase (axum 0.8.x)

* [ROAPI](https://github.com/roapi/roapi) ⭐ 3,428 | 🐛 66 | 🌐 Rust | 📅 2026-03-25: Create full-fledged APIs for static datasets without writing a single line of code. (axum 0.8)
* [wastebin](https://github.com/matze/wastebin) ⭐ 843 | 🐛 18 | 🌐 Rust | 📅 2026-08-27: A minimalist pastebin service. (axum 0.8)
* [turbo.fish](https://turbo.fish/) ([repository](https://github.com/jplatte/turbo.fish) ⚠️ Archived): Find out for yourself 😉 (archived; axum 0.8.1)
* [ReductStore](https://github.com/reductstore/reductstore) ⭐ 368 | 🐛 17 | 🌐 Rust | 📅 2026-08-28: A time series database for storing and managing large amounts of blob data. (axum 0.8.7)
* [fx](https://github.com/rikhuijzer/fx) ⭐ 325 | 🐛 25 | 🌐 Rust | 📅 2026-08-01: A (micro)blogging server that you can self-host. (axum 0.8)
* [freedit](https://github.com/freedit-org/freedit) ⭐ 313 | 🐛 12 | 🌐 Rust | 📅 2026-08-24: A forum powered by rust. (axum 0.8.7)
* [axum\_admin](https://github.com/lingdu1234/axum_admin) ⭐ 310 | 🐛 8 | 🌐 Rust | 📅 2026-06-24: An admin panel built with **axum**, Sea-orm and Vue 3. (axum 0.8.8)
* [qiluo-admin](https://github.com/chelunfu/qiluo_admin) ⭐ 235 | 🐛 1 | 🌐 Rust | 📅 2026-07-22 | Axum + SeaORM + JWT + Scheduled + Tasks + SnowId + Redis + Memory + VUE3 | DB: MySQL, Postgres, SQLite. (axum 0.8.9)
* [rgit](https://github.com/w4/rgit/) ⭐ 210 | 🐛 34 | 🌐 Rust | 📅 2025-10-01: A blazingly fast Git repository browser, compatible with- and heavily inspired by cgit. (axum 0.8)
* [clean\_axum\_demo](https://github.com/sukjaelee/clean_axum_demo) ⭐ 201 | 🐛 0 | 🌐 Rust | 📅 2025-08-09: A modern, clean-architecture Rust API server template built with Axum and SQLx. It incorporates domain-driven design, repository patterns, JWT authentication, file uploads, Swagger documentation, OpenTelemetry. (axum 0.8.3)
* [RUSTfulapi](https://github.com/robatipoor/rustfulapi) ⭐ 197 | 🐛 3 | 🌐 Rust | 📅 2025-03-06: Reusable template for building REST Web Services in Rust. Uses axum and SeaORM. (axum 0.8.1)
* [KeyCompute](https://github.com/aiqubits/keycompute) ⭐ 181 | 🐛 1 | 🌐 Rust | 📅 2026-08-29: KeyCompute is a high-performance, scalable, and ready-to-use AI computing power service platform. (axum 0.8; added on 2026.04.27)
* [CLOMonitor](https://clomonitor.io) ([repository](https://github.com/cncf/clomonitor) ⭐ 148 | 🐛 26 | 🌐 TypeScript | 📅 2026-08-21): Checks open source projects repositories to verify they meet certain best practices. (axum 0.8.8)
* [axum-rest-api-example](https://github.com/sheroz/axum-rest-api-sample) ⭐ 132 | 🐛 0 | 🌐 Rust | 📅 2026-06-06: REST API Web service in Rust using axum, JSON Web Tokens (JWT), SQLx, PostgreSQL, Redis, Docker, structured error handling, and end-to-end API tests. (axum 0.8)
* [webshelf](https://github.com/aiqubits/webshelf) ⭐ 66 | 🐛 0 | 🌐 Rust | 📅 2026-07-06: 🤘 A convenient way to develop your web service with one click. (axum 0.8.8)
* [lishuuro.org](https://github.com/uros-5/backend-lishuuro) ⭐ 28 | 🐛 0 | 🌐 Rust | 📅 2025-08-01: Small chess variant server that uses axum for the backend. (axum 0.8.3)
* [remotehiro](https://www.remotehiro.com/) is a job board with performance, accessibility, and focus in mind.  [GitHub](https://github.com/tacohirosystems/remotehiro) ⭐ 11 | 🐛 1 | 🌐 SQL | 📅 2026-08-05 (axum 0.8; added on 2026.05.02)
* [tower-mcp](https://github.com/joshrotenberg/tower-mcp) ⭐ 9 | 🐛 5 | 🌐 Rust | 📅 2026-08-28: Tower-native Model Context Protocol (MCP) implementation. (axum 0.8)
* [xidl](https://github.com/xidl/xidl) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2026-08-26: Using axum just like tonic, declare IDL, then generate server, client and OpenAPI. (axum 0.8; added on 2026.04.27)
* [gitore](https://codeberg.org/kallisti5/gitore): A fork of `rgit`. (axum 0.8)
* [Pods-Blitz](https://pods-blitz.org) Self-hosted podcast publisher. Uses the crates axum-login, password-auth, sqlx and handlebars (for HTML templates). [source code](https://codeberg.org/pods-blitz/pods-blitz)  (axum 0.8.3)

## 🖼️ Project showcase (old)

* [Svix](https://www.svix.com) ([repository](https://github.com/svix/svix-webhooks) ⭐ 3,374 | 🐛 61 | 🌐 Rust | 📅 2026-08-28): Enterprise-ready webhook service. (axum 0.7.9)
* [realworld-axum-sqlx](https://github.com/launchbadge/realworld-axum-sqlx) ⭐ 1,104 | 🐛 14 | 🌐 Rust | 📅 2023-12-30: A Rust implementation of the [Realworld](https://github.com/gothinkster/realworld) ⭐ 84,157 | 🐛 27 | 🌐 TypeScript | 📅 2026-08-26 demo app spec using axum and [SQLx](https://crates.io/crates/sqlx). (axum 0.3.4) See [fork](https://github.com/davidpdrsn/realworld-axum-sqlx) ⭐ 238 | 🐛 2 | 🌐 Rust | 📅 2024-07-25 with newer dependencies. (axum 0.7.3)
* [Rustapi](https://github.com/ndelvalle/rustapi) ⭐ 546 | 🐛 18 | 🌐 Rust | 📅 2025-02-07: RESTful API template using MongoDB. (axum 0.7.5)
* [Jotsy](https://github.com/ohsayan/jotsy) ⭐ 512 | 🐛 8 | 🌐 Rust | 📅 2022-11-28: Self-hosted notes app powered by Skytable, axum and Tokio. (axum 0.5.17)
* [Hatsu](https://github.com/importantimport/hatsu) ⭐ 258 | 🐛 10 | 🌐 Rust | 📅 2026-08-23: 🩵 Self-hosted & Fully-automated ActivityPub Bridge for Static Sites. (axum 0.7)
* [emojied](https://github.com/sekunho/emojied) ⭐ 199 | 🐛 1 | 🌐 Rust | 📅 2025-12-18: Shorten URLs to emojis! (axum 0.6)
* [Houseflow](https://github.com/gbaranski/houseflow) ⭐ 190 | 🐛 26 | 🌐 Rust | 📅 2023-04-13: House automation platform written in Rust. (axum 0.5.1)
* [Deaftone](https://github.com/Deaftone/Deaftone) ⭐ 120 | 🐛 15 | 🌐 Rust | 📅 2024-04-05: Lightweight music server. With a clean and simple API. (axum 0.7.3)
* [Pinging.net](https://www.pinging.net) ([repository](https://github.com/benhansenslc/pinging) ⭐ 100 | 🐛 10 | 🌐 TypeScript | 📅 2026-07-26): A new way to check and monitor your internet connection. (axum 0.7)
* [JWT Auth](https://github.com/Z4RX/axum_jwt_example) ⭐ 86 | 🐛 1 | 🌐 Rust | 📅 2021-12-11: JWT auth service for educational purposes. (axum 0.4)
* [notify.run](https://github.com/notify-run/notify-run-rs) ⭐ 69 | 🐛 0 | 🌐 Rust | 📅 2021-12-24: HTTP-to-WebPush relay for sending desktop/mobile notifications to yourself, written in Rust. (axum 0.3)
* [Book Management](https://github.com/lz1998/axum-book-management) ⭐ 64 | 🐛 1 | 🌐 Rust | 📅 2023-12-01: CRUD system of book-management with ORM and JWT for educational purposes. (axum 0.7)
* [axum-postgres-template](https://github.com/koskeller/axum-postgres-template) ⭐ 59 | 🐛 0 | 🌐 Rust | 📅 2024-11-16: Production-ready axum + PostgreSQL application template. (axum 0.7.6)
* [Mini RPS](https://github.com/marcodpt/minirps) ⭐ 45 | 🐛 3 | 🌐 Rust | 📅 2024-11-06: Mini reverse proxy server, HTTPS, CORS, static file hosting and template engine (minijinja). (axum 0.7.7)
* [openapi-rs](https://github.com/baerwang/openapi-rs/tree/main/examples/axum) ⭐ 45 | 🐛 0 | 🌐 Rust | 📅 2026-06-22 | This project adds a middleware layer to axum using openapi-rs, enabling automatic request validation and processing based on OpenAPI 3.1 specifications. It helps ensure that the server behavior strictly follows the OpenAPI contract. (axum 0.7)
* [sero](https://github.com/clowzed/sero) ⭐ 42 | 🐛 5 | 🌐 Rust | 📅 2024-10-04: Host static sites with custom subdomains as surge.sh does. But with full control and cool new features. (axum, sea-orm, postgresql). (axum 0.7.4)
* [dropit](https://github.com/scotow/dropit) ⭐ 41 | 🐛 1 | 🌐 Rust | 📅 2024-02-14: Temporary file hosting. (axum 0.5.13)
* [HomeDisk](https://github.com/MedzikUser/HomeDisk) ⚠️ Archived: ☁️ Fast, lightweight and Open Source local cloud for your data. (archived; axum 0.6)
* [sandbox\_axum\_observability](https://github.com/davidB/sandbox_axum_observability) ⭐ 33 | 🐛 6 | 🌐 Rust | 📅 2023-08-06 A Sandbox/showcase project to experiment axum and observability (tracing, opentelemetry, jaeger, grafana tempo,...) (axum 0.6)
* [Petclinic](https://github.com/danipardo/petclinic) ⭐ 14 | 🐛 0 | 🌐 Rust | 📅 2022-08-12: A port of Spring Framework's Petclinic showcase project to axum. (axum 0.5.13)
* [axum-http-auth-example](https://github.com/i0n/axum-http-auth-example) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2022-11-26: axum http auth example using postgres and redis. (axum 0.6.0)
* [axum-middleware-example](https://github.com/casbin-rs/axum-middleware-example) ⭐ 8 | 🐛 1 | 🌐 Rust | 📅 2026-05-15: A authorization application using axum, Casbin and Diesel, with JWT support. (axum 0.5.13)
* [circleci-hook](https://github.com/DavidS/circleci-hook) ⭐ 8 | 🐛 2 | 🌐 Rust | 📅 2023-02-04: Translate CircleCI WebHooks to OpenTelemetry traces to improve your test insights. Add detail with otel-cli to capture individual commands. Use the TRACEPARENT integration to add details from your tests. (axum 0.6.0)
* [httq](https://github.com/scotow/httq) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2023-04-17 HTTP to MQTT trivial proxy. (axum 0.6.15)
* [randoku](https://github.com/stchris/randoku) ⭐ 3 | 🐛 8 | 🌐 Rust | 📅 2026-08-15: A tiny web service which generates random numbers and shuffles lists randomly. (axum 0.7)
* [meta-cross](https://github.com/scotow/meta-cross) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2024-05-08: Tweaked version of Tic-Tac-Toe. (axum 0.6.7)
* [cobrust](https://github.com/scotow/cobrust) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2023-07-30: Multiplayer web based snake game. (axum 0.6.1)

## 📖 Tutorials

* [demo-rust-axum](https://github.com/joelparkerhenderson/demo-rust-axum) ⭐ 440 | 🐛 0 | 🌐 Rust | 📅 2025-07-13: Demo of Rust and axum
* [axum-tutorial](https://github.com/programatik29/axum-tutorial) ⭐ 148 | 🐛 0 | 🌐 Rust | 📅 2024-11-07: axum tutorial for beginners. [website](https://programatik29.github.io/axum-tutorial/)
* [Rust on Nails](https://rust-on-nails.com/): A full stack architecture for Rust web applications
* [Getting Started with Axum](https://carlosmv.hashnode.dev/getting-started-with-axum-rust): axum tutorial, GET, POST endpoints and serving files
* [Using Rust, Axum, PostgreSQL, and Tokio to build a Blog](https://spacedimp.com/blog/using-rust-axum-postgresql-and-tokio-to-build-a-blog/)
* [API Development with Rust](https://rust-api.dev/docs/front-matter/preface/): REST APIs based on axum
* [axum-rest-api-postgres-redis-jwt-docker](https://sheroz.com/pages/blog/rust-axum-rest-api-postgres-redis-jwt-docker.html): Getting started with REST API Web Services in Rust using Axum, PostgreSQL, Redis, and JWT
* [Building a SaaS with Rust & Next.js](https://joshmo.bearblog.dev/lets-build-a-saas-with-rust/) A tutorial for combining Next.js with Rust via axum to make a SaaS.

## 📺 Videos

* 2022.07.06 - [Introduction to axum (talk)](https://www.youtube.com/watch?v=ETdmhh7OQpA): David Pedersen on Axum - Talk about axum from the Copenhagen Rust Meetup - (42 min; axum 0.5)
* 2022.12.22 - [Introduction to axum](https://www.youtube.com/playlist?list=PLrmY5pVcnuE-_CP7XZ_44HN-mDrLQV4nS): YouTube playlist by Brooks Builds (brookzerker) - (10 hours; axum 05-06 with an update to 0.8.1)
* 2023.04.09 - [Rust Axum Full Course](https://www.youtube.com/watch?v=XZtlD_m59sM): YouTube video by Jeremy Chone - (1 hour 20 min; GitHub repo updated to axum 0.7)
* 2023.07.28 - [Decrusting the axum crate](https://www.youtube.com/watch?v=Wnb_n5YktO8) by Jon Gjengset (2 hours 12 min)
* 2025.06.03 - [Build REST APIs with the Rust Axum Web Framework](https://www.youtube.com/watch?v=7RlVM0D4CEA) by Trevor Sullivan (1 hour 39 min)
* 2025.10.16 - [Creating an Axum Web Server in Rust is easy!](https://www.youtube.com/watch?v=FDWKlJmHv6k) by Flo Woelki (21 min)
* 2026.04.28 - [axum 0.8.x](https://academy.code-maven.com/c/rust-axum-v0.8-2026) by Gabor Szabo (registration required; axum 0.8; 6 hours 53 min)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-29._
