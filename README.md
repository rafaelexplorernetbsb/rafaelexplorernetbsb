<h1 align="left">Rafael — Tech Stack & Architecture</h1>

Profissional de software focado em **backends escaláveis**, **workflows** e **integrações empresariais**.
Trabalho com Python/Django no core, Next.js no frontend e Salesforce para operações.

---

## 🧩 Core Stack (prod)
- **Backend:** Python 3.x • Django + Django-Ninja • Celery • Pydantic • Poetry
- **Frontend:** Next.js (React/TypeScript) • Tailwind • shadcn/ui • React Hook Form • Zod
- **Data & Cache:** PostgreSQL • Redis
- **Mensageria/Jobs:** RabbitMQ • Celery Beat • n8n (integrações)
- **Observabilidade:** Sentry • healthchecks • métricas custom
- **Cloud/DevOps:** Docker • Vercel • GitHub Actions
- **Salesforce:** Apex • LWC • Flow Builder • Metadata API
- **Fiscais/Telecom:** NFSe/NFCom (ABRASF 2.01, SOAP/ass. digital) • ACS/SmartOLT

## 🏗️ Padrões & práticas
- **DDD leve**, **boundary contexts**, **service layer** e **adapters** para integrações
- **Conventional Commits** + semver • CI/CD com lint/test/build
- **12-factor** • configs por ambiente • secrets seguros
- **Idempotência** em rotinas de cobrança e emissão fiscal
- **Métricas de produto** antes de escalar features

## 🔌 Integrações recorrentes
- WhatsApp Business (360dialog) • Gateways de NFSe/NFCom • Salesforce (REST/SOAP)
- Directus/RSS • MinIO/S3 • SmartOLT/ACS

## 📚 Exemplos de projetos (repos pinados)
- `talktome-crm` — CRM modular + **editor visual de workflows** (multi-tenant).
- `workflows-editor` — Editor (React Flow) com nodes, validações e persistência.
- `retention-ai` — Agente de retenção/negociação (prompts, regras, WhatsApp).
- `integra-notas` — NFSe/NFCom (ABRASF 2.01), SOAP, **assinatura digital**, exemplos XML.
- `news-portal` — Portal TS com pipelines de conteúdo e deploy automatizado.
- `ops-scripts` — utilitários (migrations, jobs, tasks Celery, healthchecks).

> Cada repo tem: README claro (runbook), **docker compose** de dev, exemplos, e CI básico.

## 🛠️ Ferramentas do dia a dia
`poetry` • `ruff`/`black` • `pytest` • `pre-commit` • `pnpm` • `eslint`/`biome` • `turbo` • `taskfile` • `httpie` • `mkcert`

## 📫 Contato
- Site: https://talktome.com.br  
- E-mail: rafaelexplorernetbsb@gmail.com  
- LinkedIn: *seu_link_aqui*
