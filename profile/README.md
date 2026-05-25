<div align="center">

<img src="https://raw.githubusercontent.com/is-pinoy-dev/.github/main/assets/banner.gif" alt="is-pinoy.dev banner" width="100%" />

# 🇵🇭 is-pinoy.dev

**Free `*.is-pinoy.dev` subdomains for Filipino developers.**

Register your own subdomain in minutes — no cost, no gatekeeping, just open source.

[![Subdomains](https://img.shields.io/badge/subdomains-register%20yours-blue?style=flat-square)](https://github.com/is-pinoy-dev/domains)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)](https://github.com/is-pinoy-dev/domains/pulls)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](https://github.com/is-pinoy-dev/.github/blob/main/LICENSE)
[![Community](https://img.shields.io/badge/community-discord-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/MVrgEfFExh)

</div>

---

## ✨ What is is-pinoy.dev?

**is-pinoy.dev** is a community-driven project that gives Filipino developers a free, professional-looking subdomain under `*.is-pinoy.dev`. Whether you're building a portfolio, a side project, or a dev tool — you deserve a domain that represents you.

Inspired by projects like [is-a.dev](https://is-a.dev) and [js.org](https://js.org), built with 🤍 by and for the Filipino dev community.

---

## 🚀 Get Your Subdomain

Getting your own `yourname.is-pinoy.dev` is as simple as opening a pull request:

1. **Fork** [`is-pinoy-dev/domains`](https://github.com/is-pinoy-dev/domains)
2. **Add** a JSON file in `subdomains/yourname.json`
3. **Open a PR** — our bot validates it automatically
4. **Get merged** and your subdomain goes live 🎉

```json
{
  "subdomain": "yourname",
  "owner": {
    "github": "yourusername"
  },
  "record": {
    "type": "CNAME",
    "value": "yoursite.vercel.app"
  }
}
```

> 📖 Read the full guide in [is-pinoy-dev/domains](https://github.com/is-pinoy-dev/domains)

---

## 🗂️ Repositories

| Repo | Description |
|------|-------------|
| [`.github`](https://github.com/is-pinoy-dev/.github) | Org-wide community health files, templates, and this profile |
| [`domains`](https://github.com/is-pinoy-dev/domains) | 🌐 Subdomain registry — register yours via a pull request |
| [`ecosystem`](https://github.com/is-pinoy-dev/ecosystem) | 🔧 Monorepo — CLI, schemas, validator, and platform tooling |

---

## 🛠️ Ecosystem

The [`ecosystem`](https://github.com/is-pinoy-dev/ecosystem) monorepo powers everything under the hood:

- **`packages/cli`** — Register and manage your subdomain from the terminal
- **`packages/schemas`** — JSON schemas for subdomain validation
- **`packages/validator`** — Shared validation logic used in CI
- **`apps/web`** — The is-pinoy.dev website and docs

---

## 🤝 Contributing

We welcome contributions of all kinds — code, docs, ideas, and bug reports.

- **Register a subdomain** → [`is-pinoy-dev/domains`](https://github.com/is-pinoy-dev/domains)
- **Improve the platform** → [`is-pinoy-dev/ecosystem`](https://github.com/is-pinoy-dev/ecosystem)
- **Report issues** → [`is-pinoy-dev/.github`](https://github.com/is-pinoy-dev/.github/issues)

Please read our [Contributing Guide](https://github.com/is-pinoy-dev/.github/blob/main/CONTRIBUTING.md) and [Code of Conduct](https://github.com/is-pinoy-dev/.github/blob/main/CODE_OF_CONDUCT.md) before getting started.

---

## 📬 Connect

- 💬 **Discord** — [Join our community](https://discord.gg/MVrgEfFExh)

---

<div align="center">

Made with 🤍 by Filipino developers, for Filipino developers.

**[is-pinoy.dev](https://is-pinoy.dev)**

</div>
