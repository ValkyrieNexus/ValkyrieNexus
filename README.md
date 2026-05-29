# Hey, I'm Dein

**Full-Stack Engineer & Founder** &nbsp;|&nbsp; U.S. Veteran &nbsp;|&nbsp; Platforms · Web Applications · Secure Infrastructure

> I design, build, and ship complete products — then run the hardened infrastructure they live on.

---

I build software end to end. The interface, the application and API layers, the data model, the CI/CD pipeline, and the zero-trust infrastructure underneath — I own the whole stack, from first commit to hardened production.

I'm a U.S. Veteran who transitioned into tech with a mission-first mindset: build things that are reliable, defensible, and intentional. Every architectural decision is deliberate — I want to understand what each component does, how the pieces connect, and how to make the result elastic, scalable, and secure at its core.

## Ventures

### Valkyrie Nexus — Platform & Security Engineering

My engineering brand: full-stack web platforms, container orchestration, identity-aware access, and security observability — built and operated from bare metal to production. Public presence across two domains, one for portfolio and consulting, one for engineering notes and architecture documentation.

<a href="https://valkyrienexus.com">valkyrienexus.com</a> &nbsp;·&nbsp; <a href="https://valkyrienexus.dev">valkyrienexus.dev</a>

### StoneFyr — Design & Engineering Studio

A small business I founded around custom design and 3D-printing engineering. StoneFyr pairs a public storefront with a purpose-built inventory and order management system — designed, built, and deployed in house on a modern edge stack (SolidStart on Cloudflare Workers, D1, and R2).

<a href="https://stonefyr.com">stonefyr.com</a>

## Flagship Application

### C²FHQ — Real-Time Faction Command Center

A web-based command center for [Torn City](https://www.torn.com) factions and my most substantial application to date — real-time war tracking, organized-crime lifecycle management, member analytics, and financial accounting.

- **Customizable dashboard** — drag-and-drop grid of 18 widgets with persistent per-user layouts and tiered auto-refresh.
- **War management** — live attack feeds, chain reporting, post-war payout distribution, and configurable rank tiers.
- **Organized crimes** — full lifecycle (recruiting → planning → completed → historical) with checkpoint tracking, reward estimation, and payout calculation.
- **Architecture in motion** — v1 runs in production; v2 is a deliberate consolidation from 28 Rust/gRPC microservices to a single Rust (Axum) monolith with a SolidStart frontend and Cloudflare Durable Objects for sub-30 ms real-time state, migrated via a strangler-fig cutover with zero downtime.

Live at <a href="https://c2fhq.com">c2fhq.com</a>.

## Selected Web Work

Production websites and platforms I design, build, and maintain — not brochure pages, but full applications with real back-office features.

| Project | What it does | Stack |
|---------|--------------|-------|
| **[Air Assault Fireworks](https://airassaultfireworks.com)** | Customer reservation site + back-office storefront with an admin analytics dashboard | SolidStart · Cloudflare Workers · D1 · R2 |
| **[Matt's Delicious Meat](https://mattsdeliciousmeat.com)** | BBQ catering site with menu and lead capture | SolidStart · Cloudflare Workers |
| **[Arnold's Appliance Repair](https://arnoldsappliancerepair.com)** | Service business site for the Greater Tulsa area | SolidStart · TypeScript |
| **[The Veteran Alliance](https://theveteranalliance.com)** | Founding member — contributed to the digital platform and web presence | In active development |
| **[Valkyrie Nexus](https://valkyrienexus.com)** | Two-domain portfolio + engineering-notes platform with interactive 3D scenes | SolidStart · Three.js · Turborepo · Docker |

## Open Source

**[QRcodeGen](https://github.com/ValkyrieNexus/QRcodeGen)** — a free Autodesk Fusion add-on that generates QR codes as extruded 3D bodies for multi-color 3D printing. Supports text, URL, vCard, WiFi, and batch-sequence modes, on-face placement, and per-module color separation. Pure-Python, zero external dependencies.

## Infrastructure & Homelab

I run a self-hosted platform that mirrors enterprise architecture patterns — a working environment where I build, break, and harden real systems.

| Layer | Technology | Purpose |
|-------|-----------|---------|
| Virtualization | Proxmox VE | Hypervisor for isolated workloads |
| External Access | Cloudflare Tunnels | Zero-trust ingress, no exposed ports |
| Routing | Traefik | Dynamic reverse proxy with auto-TLS |
| Identity & Auth | Authentik | SSO, MFA, and policy-based access control |
| Orchestration | K3s | Lightweight Kubernetes for service deployment |
| Security & Observability | Wazuh | SIEM, intrusion detection, log analysis |
| Containerization | Docker | Multi-stage builds, non-root, read-only filesystems |
| Web Serving | Nginx | Rate limiting, security headers, CSP |
| CI/CD | GitHub Actions | Automated lint, test, build, scan, deploy |

This isn't a tech list — it's a trust chain. Traffic enters through Cloudflare, gets routed by Traefik, authenticated by Authentik, served from hardened containers, and monitored by Wazuh. Every layer has a job.

## Certifications & Learning

| Status | Certification |
|--------|--------------|
| **Earned** | CompTIA Network+ |
| **In Progress** | AWS Certified Cloud Ops Engineer – Associate |
| **Planned** | CompTIA Security+ |

## Tech & Tools

**Development:** TypeScript · SolidJS/SolidStart · Rust (Axum) · Node.js · Three.js · Python

**Edge & Data:** Cloudflare Workers · Durable Objects · D1 · R2 · PostgreSQL · Redis

**Infrastructure:** Proxmox · Docker · K3s · Nginx · Traefik · Cloudflare Tunnels

**Security:** Wazuh · Authentik · CSP · Container Hardening · Zero-Trust Architecture

**Operations:** GitHub Actions · GitOps · pnpm · Turborepo

**Web Craft:** Responsive Design · SSR · Accessibility (WCAG AA) · Performance Optimization

---
## Contact

**Email**: admin@valkyrienexus.com

---
## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats-tau-bice-66.vercel.app/api?username=ValkyrieNexus&show_icons=true&theme=github_dark&hide_border=true&bg_color=0A0A0F&title_color=F0B940&icon_color=C9972E&text_color=CCCCCC" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats-tau-bice-66.vercel.app/api/top-langs/?username=ValkyrieNexus&layout=compact&theme=github_dark&hide_border=true&bg_color=0A0A0F&title_color=F0B940&text_color=CCCCCC" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=ValkyrieNexus&theme=dark&hide_border=true&background=0A0A0F&ring=F0B940&fire=F0B940&currStreakLabel=F0B940&sideLabels=CCCCCC&dates=666666" alt="GitHub Streak" />
</p>
