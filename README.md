# ⚡ DevOps World

Tu guía esencial para entrar al mundo DevOps moderno. Sin relleno, solo lo que necesitas saber.

🌐 **Live:** [devops-world-paula.pages.dev](https://devops-world-paula.pages.dev)

## ¿Qué incluye?

- **Roadmap DevOps** — 5 pilares fundamentales en orden lógico
- **Lenguajes & Frameworks** — Tablas comparativas interactivas (Backend, Frontend, IaC)
- **Cloud Providers** — AWS vs GCP vs Azure vs Cloudflare
- **Servicios Cloudflare** — Pages, Workers, D1, KV, R2, AI Gateway, Zero Trust
- **CI/CD Tools** — GitHub Actions, GitLab CI, Jenkins y más
- **Docker & Kubernetes** — Conceptos esenciales con ejemplos
- **Noticias Tech** — Carga en tiempo real desde Hacker News (sin API key en frontend)

## Stack

- [Astro](https://astro.build) — Framework web estático
- [Cloudflare Pages](https://pages.cloudflare.com) — Hosting y deploy

## Desarrollo local

```bash
npm install
npm run dev
```

## Deploy

```bash
npm run build
wrangler pages deploy dist --project-name devops-world-paula
```
