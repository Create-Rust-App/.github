# Contributing to Create Rust App

Thanks for contributing!

This repository hosts the organization profile (`profile/`) and the shared
community health files (`CODE_OF_CONDUCT.md`, `SECURITY.md`, `FUNDING.yml`,
`.github/` templates) for the [Create-Rust-App](https://github.com/Create-Rust-App)
organization. CLI and template contributions belong in their own repositories
once they land (`create-rust-app`, `cra-templates`).

Please note we have a [Code of Conduct](./CODE_OF_CONDUCT.md) — follow it in
all your interactions with the project.

## Prerequisites

- `git`
- A text editor
- Optional: `pre-commit` (`pre-commit install`)
- For future Rust work: [rustup](https://rustup.rs) with the pinned stable
  toolchain (`rustc --version`)

## Setup

```bash
git clone https://github.com/Create-Rust-App/.github.git
cd .github
```

## Workflow

1. Open or use an existing GitHub issue.
2. Branch from `main`: `feat/<issue>-short-slug`.
3. Make a focused change (one issue per PR).
4. Verify your change locally (see below).
5. Open a **ready-for-review** PR with `Closes #<issue>`.
6. Wait for review before merging.

## Verification

This repository has no test suite of its own. Before opening a PR, run:

```bash
python3 -c "import yaml; yaml.safe_load(open('FUNDING.yml'))"
python3 -c "import xml.dom.minidom; xml.dom.minidom.parse('profile/banner.svg')"
```

And confirm relative links (such as `./banner.svg` in `profile/README.md`)
resolve from the file that references them.

## Code style

- English for commits, PRs, and docs.
- Keep Markdown lines tidy; match the style of the sibling
  [Create-Vlang-App/.github](https://github.com/Create-Vlang-App/.github) files.
- For future Rust code: run `cargo fmt` and `cargo clippy`; prefer clear names
  over cleverness.
