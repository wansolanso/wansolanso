<!-- wansolanso — GitHub profile README -->
<!-- Concept: "you are the infrastructure." The profile reads like a live system. -->
<!-- Repo: create a public repo named exactly `wansolanso`, put this README.md at its root. -->

<!-- ───────────────────────── HEADER: logo + animated typing ───────────────────────── -->

<p align="center">
  <a href="https://atalho.dev"><img src="assets/atalho-logo.svg" width="84" alt="Atalho" /></a>
</p>

<p align="center">
  <a href="https://atalho.dev">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&pause=1200&color=5EEAD4&center=true&vCenter=true&width=720&height=70&lines=%24+whoami;I+ship+the+whole+stack+%E2%80%94+infra+to+UI.;Infrastructure+is+a+product.+I+ship+it+like+one.;multi-tenant+%7C+zero-trust+%7C+infra-as-code" />
      <img alt="$ whoami — I ship the whole stack, infra to UI" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&pause=1200&color=0F766E&center=true&vCenter=true&width=720&height=70&lines=%24+whoami;I+ship+the+whole+stack+%E2%80%94+infra+to+UI.;Infrastructure+is+a+product.+I+ship+it+like+one.;multi-tenant+%7C+zero-trust+%7C+infra-as-code" />
    </picture>
  </a>
</p>

<p align="center">
  <code>uptime: building since day 0</code> &nbsp;•&nbsp;
  <code>region: br-south</code> &nbsp;•&nbsp;
  <code>status: 🟢 shipping</code>
</p>

<!-- ───────────────────────── WHOAMI as Terraform ───────────────────────── -->

### ▸ `cat identity.tf` <img align="right" alt="# about" src="https://img.shields.io/badge/%23%20about-0d1117?style=flat&labelColor=0d1117" />

```hcl
resource "human" "matheus" {
  role        = "Founder / Platform Engineer"
  building    = "Atalho — multi-tenant SaaS, infra to UI"
  obsessed_by = ["secure isolation", "clean abstractions", "systems that don't page you at 3am"]

  philosophy {
    infra    = "cattle, not pets"
    secrets  = "never at rest, never in git"
    tenants  = "isolated by design, not by convention"
  }

  lifecycle {
    prevent_destroy = true   # still shipping
  }
}
```

<!-- ───────────────────────── SYSTEMCTL STATUS ───────────────────────── -->

### ▸ `systemctl status matheus` <img align="right" alt="# status" src="https://img.shields.io/badge/%23%20status-0d1117?style=flat&labelColor=0d1117" />

```console
● matheus.service — full-stack engineer who owns the platform
     Loaded: loaded (/etc/founder/matheus.service; enabled)
     Active: active (running) — ships infra + product, solo when it counts
   Main PID: 1 (relentless)
     Memory: multi-tenant architecture, Vault, IaC, ERP/CRM internals
     CGroup: platform → cloud → security → product
```

<!-- ───────────────────────── STACK ───────────────────────── -->

### ▸ `terraform state list` <img align="right" alt="# stack" src="https://img.shields.io/badge/%23%20stack-0d1117?style=flat&labelColor=0d1117" />

```text
module.languages     TypeScript · Node.js · Python · Go
module.infra         Terraform · Oracle Cloud (OCI) · Vault · Docker · GitHub Actions
module.data          PostgreSQL · SQLite
module.doctrine      zero-trust · instance-per-tenant · crypto-shred · IaC everything
```

<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-05122A?style=flat&logo=typescript&logoColor=3178C6&labelColor=05122A" />
  <img alt="Go" src="https://img.shields.io/badge/-Go-05122A?style=flat&logo=go&logoColor=00ADD8&labelColor=05122A" />
  <img alt="Python" src="https://img.shields.io/badge/-Python-05122A?style=flat&logo=python&logoColor=FFD43B&labelColor=05122A" />
  <img alt="Terraform" src="https://img.shields.io/badge/-Terraform-05122A?style=flat&logo=terraform&logoColor=844FBA&labelColor=05122A" />
  <img alt="Oracle Cloud" src="https://img.shields.io/badge/-Oracle%20Cloud-05122A?style=flat&logo=oracle&logoColor=F80000&labelColor=05122A" />
  <img alt="Vault" src="https://img.shields.io/badge/-Vault-05122A?style=flat&logo=vault&logoColor=FFEC6E&labelColor=05122A" />
  <img alt="Docker" src="https://img.shields.io/badge/-Docker-05122A?style=flat&logo=docker&logoColor=2496ED&labelColor=05122A" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/-PostgreSQL-05122A?style=flat&logo=postgresql&logoColor=4169E1&labelColor=05122A" />
</p>

<!-- ───────────────────────── FOOTER ───────────────────────── -->

<p align="center">
  <a href="https://atalho.dev">
    <img alt="atalho.dev — legal-tech SaaS" src="https://img.shields.io/badge/atalho.dev-0F766E?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  &nbsp;
  <a href="mailto:matheus@atalho.dev">
    <img alt="email matheus@atalho.dev" src="https://img.shields.io/badge/%24_ping_me-5EEAD4?style=for-the-badge&logo=gmail&logoColor=05122A" />
  </a>
</p>

<p align="center"><sub>Building <a href="https://atalho.dev">Atalho</a> — legal-tech SaaS. Most of the platform lives in private repos.</sub></p>

<p align="center"><sub><code># EOF — still running. don't <kbd>Ctrl</kbd>+<kbd>C</kbd>.</code></sub></p>
