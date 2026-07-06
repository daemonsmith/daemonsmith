# Hi, I'm Dara

**Infrastructure and security engineer.** I run production infrastructure, harden it, and automate it, and I build the full-stack apps that sit on top. Working with clients worldwide.

Pentera Security Level 3 and Microsoft SC-300 certified. 100% Job Success on Upwork.

<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/Remix-000000?style=flat&logo=remix&logoColor=white" />
</p>

### What I do

I keep production systems running, secure, and automated:

- Build deployment pipelines that ship with zero downtime and roll themselves back when something breaks.
- Track down why a server is slow or acting compromised, and prove the cause with evidence instead of guesswork.
- Harden servers that are under constant attack: locked-down access, automatic blocking of bad actors, no successful break-ins.
- Set up firewalls and secure remote access for small teams, working fully remote.

### What I'm building right now

- **[MXVerify](https://mxverify.io):** an email verification SaaS. The interesting part is the verification engine: a hand-rolled SMTP prober over raw TCP that walks the full handshake, reads the reply codes, and sorts every address into a 13-status risk model. It also ships a ZeroBounce-compatible API so existing tools can drop it in. TypeScript, Express, BullMQ, Redis, Stripe billing.
- **[Cricutny](https://cricutny.com):** a digital-goods marketplace and subscription platform. My work here is payment reliability: Stripe idempotency, distributed Redis locks, and reconciling orphaned subscriptions so nobody gets double-billed. Remix, Prisma, MariaDB, 108 migrations deep.
- **[SSUP Store](https://ssup.store):** a print-on-demand store with automated Printful fulfillment, Stripe (including Apple and Google Pay), magic-link auth, and four languages. Remix on the front, PayloadCMS on the back, talking over a generated GraphQL client.
- **Playminoo:** a Django dashboard for a live Minecraft network. I wrote the Source RCON protocol client from scratch after the off-the-shelf library broke under Gunicorn's threads. Role-based moderation, full command audit logging, MariaDB.

### Tech I reach for

**Systems & security:** Linux, Nginx, Caddy, FortiGate, Pentera, hardening, incident response
**Cloud & infra:** AWS, GCP, Terraform, Ansible, Docker
**Ops & observability:** PM2, systemd, Prometheus, Grafana, Cloudflare
**Data:** PostgreSQL, MariaDB, MongoDB, Redis
**Languages & web:** TypeScript / Node.js, Python, Bash, Express, Remix, Django

### Open source

- **[oracle-arm-llm](https://github.com/daemonsmith/oracle-arm-llm):** a containerized LLM setup (llama.cpp + Open-WebUI) tuned for the Oracle Cloud ARM free tier, with hot model-switching.
- **[postgres-backup-restore](https://github.com/daemonsmith/postgres-backup-restore):** automated Postgres backups with 30-second restore, using Docker and MinIO.
- **[docker-monitoring-stack](https://github.com/daemonsmith/docker-monitoring-stack):** Prometheus and Grafana container monitoring, up in under two minutes.

### Reach me

- Email: temidaraadekoya@gmail.com
- LinkedIn: [temidara-adekoya](https://linkedin.com/in/temidara-adekoya-a5966124b)
- Upwork: [Temidara on Upwork](https://www.upwork.com/freelancers/~01eb1af01de029d49a)
