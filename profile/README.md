<div align="center">

<img src="./banner.svg" alt="Create Rust App" width="100%" />

# Create Rust App

**One command. Any Rust stack.**

> The scaffolding toolkit for the [Rust programming language](https://www.rust-lang.org), built alongside [Create Node App](https://github.com/Create-Node-App).

[![Crates.io](https://img.shields.io/crates/v/create-awesome-rust-app.svg?style=flat-square)](https://crates.io/crates/create-awesome-rust-app)
[![Release](https://img.shields.io/github/v/release/Create-Rust-App/create-rust-app?filter=create-rust-app%40*&style=flat-square&label=Release)](https://github.com/Create-Rust-App/create-rust-app/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://github.com/Create-Rust-App/create-rust-app/blob/main/LICENSE)
[![Rust](https://img.shields.io/badge/Rust-stable-orange?style=flat-square)](https://www.rust-lang.org)
[![Discord](https://img.shields.io/discord/1527933660764831825?style=flat-square&label=Discord&logo=discord&logoColor=white)](https://discord.gg/bR5VyATgka)

[CLI](https://github.com/Create-Rust-App/create-rust-app) · [Templates](https://github.com/Create-Rust-App/cra-templates) · [Website](https://create-awesome-rust-app.vercel.app) · [Releases](https://github.com/Create-Rust-App/create-rust-app/releases)

</div>

---

## What is this?

`Create Rust App` brings the composition-first scaffolding philosophy of [create-awesome-node-app](https://github.com/Create-Node-App/create-node-app) to the Rust ecosystem.

Pick a template. Layer extensions. Bootstrap production-ready Rust projects without the usual setup overhead.

Install the CLI, then scaffold:

```bash
curl -fsSL https://create-awesome-rust-app.vercel.app/install.sh | sh
create-rust-app my-api --template axum-starter
```

Or straight from crates.io:

```bash
cargo install create-awesome-rust-app --locked
```

---

## Community

Questions, ideas, template requests, and collaboration are welcome in the Create Awesome community.

[![Join the Discord community](https://img.shields.io/discord/1527933660764831825?label=Join%20Discord&logo=discord&logoColor=white)](https://discord.gg/bR5VyATgka)

---

## About the author

This project is maintained by [Ulises Jeremias](https://github.com/ulises-jeremias), author of [Create Node App](https://github.com/Create-Node-App) and several foundational libraries in the V ecosystem:

| Project | Description |
|---------|-------------|
| [vlang/vsl](https://github.com/vlang/vsl) | V Scientific Library: linear algebra, stats, optimization |
| [vlang/vtl](https://github.com/vlang/vtl) | V Tensor Library: n-dimensional tensors for V |
| [ulises-jeremias/rxv](https://github.com/ulises-jeremias/rxv) | Reactive Extensions for V |
| [vlang/setup-v](https://github.com/vlang/setup-v) | GitHub Action to set up V in CI workflows |

---

## Available Templates

| Template | Stack | Status |
|----------|-------|--------|
| [axum-starter](https://github.com/Create-Rust-App/cra-templates/tree/main/templates/axum-starter) | Production Axum HTTP API: feature modules, Tokio, tracing, fmt/clippy/test gates | ✅ Shipped |
| [cli-starter](https://github.com/Create-Rust-App/cra-templates/tree/main/templates/cli-starter) | Production clap CLI: feature subcommands, tracing, shell completions | ✅ Shipped |
| [leptos-starter](https://github.com/Create-Rust-App/cra-templates/tree/main/templates/leptos-starter) | Leptos fullstack: SSR pages with htmx interactivity on Axum | ✅ Shipped |
| [worker-starter](https://github.com/Create-Rust-App/cra-templates/tree/main/templates/worker-starter) | Tokio background worker: typed job queue, pool, scheduler, graceful shutdown | ✅ Shipped |
| [lib-starter](https://github.com/Create-Rust-App/cra-templates/tree/main/templates/lib-starter) | Publishable library: feature modules, doc examples, demo binary | ✅ Shipped |
| [tonic-starter](https://github.com/Create-Rust-App/cra-templates/tree/main/templates/tonic-starter) | tonic gRPC microservice: Protobuf contract, reflection, graceful shutdown | ✅ Shipped |

Catalog: [`cra-templates`](https://github.com/Create-Rust-App/cra-templates)

---

## Available Extensions

18 extensions in [`cra-templates`](https://github.com/Create-Rust-App/cra-templates/tree/main/extensions), composed onto templates without forking:

- **Axum** (11): CORS, JWT auth, OpenAPI docs, SQLx, request IDs, timeouts, compression, rate limiting, security headers, OpenTelemetry, Docker
- **Cross-cutting** (4): GitHub setup, GitLab setup, dev containers, pre-commit hooks
- **Specialized** (3): CLI man pages, Criterion benches, tonic health checks

---

## Status

**✅ Shipped**: the CLI ([`create-rust-app`](https://github.com/Create-Rust-App/create-rust-app), `0.4.0` — [crates.io](https://crates.io/crates/create-awesome-rust-app)) and the official template bank ([`cra-templates`](https://github.com/Create-Rust-App/cra-templates): 6 templates, 18 extensions) are live. This repository hosts the organization profile and shared community files.

The Rust counterpart of:

→ **[create-awesome-node-app.vercel.app](https://create-awesome-node-app.vercel.app)**

---

## 👥 Contributors

### `create-rust-app`: CLI

<a href="https://github.com/Create-Rust-App/create-rust-app/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Create-Rust-App/create-rust-app" alt="Contributors for create-rust-app" />
</a>

### `cra-templates`: Templates & Extensions

<a href="https://github.com/Create-Rust-App/cra-templates/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Create-Rust-App/cra-templates" alt="Contributors for cra-templates" />
</a>

Made with [contrib.rocks](https://contrib.rocks).

---

## Part of the Create Awesome App ecosystem

| Org | Stack | Status |
|-----|-------|--------|
| [Create-Node-App](https://github.com/Create-Node-App) | Node.js, TypeScript | ✅ Production |
| [Create-Python-App](https://github.com/Create-Python-App) | Python | ✅ Production |
| [Create-Vlang-App](https://github.com/Create-Vlang-App) | V language | ✅ Shipped (`0.1.0`) |
| [Create-Rust-App](https://github.com/Create-Rust-App) | Rust | ✅ Shipped (`0.4.0`) |
