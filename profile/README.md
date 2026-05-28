<p align="center">
  <img src="./assets/nexa-banner.svg" alt="Nexa - cold-chain operations platform banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/upc-pre-202610-1asi0730-12242-king">
    <img alt="Organization" src="https://img.shields.io/badge/GitHub-upc--pre--202610--1asi0730--12242--king-0F274A?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <img alt="Academic project" src="https://img.shields.io/badge/UPC-Aplicaciones%20Web-0EA5E9?style=for-the-badge" />
  <img alt="Cycle" src="https://img.shields.io/badge/2026--10-Team%20King-38BDF8?style=for-the-badge" />
</p>

<h1 align="center">Nexa</h1>

<p align="center">
  <strong>Cold-chain operations platform for coordinated B2B refrigerated commerce.</strong>
</p>

<p align="center">
  Nexa is an academic software project focused on helping teams coordinate sales, logistics,
  warehouse inventory, invoicing, and catalog operations in cold-chain business workflows.
</p>

<p align="center">
  <img src="./assets/nexa-logo.svg" alt="Nexa logo" width="112" />
</p>

---

## Repository Map

<table>
  <tr>
    <td width="50%">
      <h3><a href="https://github.com/upc-pre-202610-1asi0730-12242-king/nexa-webapp">nexa-webapp</a></h3>
      <p>Frontend web application for operational workflows and user-facing platform screens.</p>
      <p>
        <img alt="Vue 3" src="https://img.shields.io/badge/Vue%203-35495E?logo=vue.js&logoColor=4FC08D" />
        <img alt="Vite" src="https://img.shields.io/badge/Vite-0F274A?logo=vite&logoColor=FFD62E" />
        <img alt="PrimeVue" src="https://img.shields.io/badge/PrimeVue-0EA5E9" />
      </p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/upc-pre-202610-1asi0730-12242-king/nexa-website">nexa-website</a></h3>
      <p>Public website and landing experience for presenting the Nexa product concept.</p>
      <p>
        <img alt="Website" src="https://img.shields.io/badge/Website-public%20site-2563EB" />
        <img alt="Brand" src="https://img.shields.io/badge/Brand-Nexa-38BDF8" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3><a href="https://github.com/upc-pre-202610-1asi0730-12242-king/nexa-platform">nexa-platform</a></h3>
      <p>Platform and backend work area for API, domain, and future infrastructure concerns.</p>
      <p>
        <img alt="ASP.NET Core" src="https://img.shields.io/badge/ASP.NET%20Core-planned-512BD4?logo=dotnet&logoColor=white" />
        <img alt="Firebase" src="https://img.shields.io/badge/Firebase-future%20deployment-FFCA28?logo=firebase&logoColor=111827" />
      </p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/upc-pre-202610-1asi0730-12242-king/nexa-report">nexa-report</a></h3>
      <p>Academic report, product research, architecture documentation, and project evidence.</p>
      <p>
        <img alt="Documentation" src="https://img.shields.io/badge/Documentation-report-0F274A" />
        <img alt="UPC" src="https://img.shields.io/badge/UPC-course%20evidence-0EA5E9" />
      </p>
    </td>
  </tr>
</table>

---

## Product Focus

Nexa explores how a B2B cold-chain team can align commercial decisions with inventory,
dispatch, and documentation workflows. The project emphasizes traceability, bounded contexts,
and a clean web interface for internal operations.

| Area | Project Focus |
| --- | --- |
| Sales | Order intake, commercial validation, customer requests, and sales coordination. |
| Logistics | Dispatch planning, delivery tracking, and operational visibility. |
| Warehouse | Inventory lots, stock movements, warehouse status, and cold-chain handling. |
| Invoicing | Business documents, invoicing support, and document status follow-up. |
| Catalog Management | Product catalog organization for refrigerated B2B commerce. |

```mermaid
flowchart LR
  C[Catalog Management] --> S[Sales]
  S --> W[Warehouse]
  W --> L[Logistics]
  S --> I[Invoicing]
  L --> I
```

---

## Technology Stack

| Layer | Technologies |
| --- | --- |
| Frontend | Vue 3, Vite, PrimeVue, JavaScript, HTML, CSS |
| Platform | ASP.NET Core as planned backend direction |
| Deployment | Firebase considered for future deployment |
| Documentation | Markdown, diagrams, academic report assets |
| Collaboration | GitHub repositories, pull requests, issue tracking |

<p>
  <img alt="Vue 3" src="https://img.shields.io/badge/Vue%203-0F274A?logo=vue.js&logoColor=4FC08D" />
  <img alt="Vite" src="https://img.shields.io/badge/Vite-0F274A?logo=vite&logoColor=FFD62E" />
  <img alt="PrimeVue" src="https://img.shields.io/badge/PrimeVue-0EA5E9" />
  <img alt="ASP.NET Core" src="https://img.shields.io/badge/ASP.NET%20Core-2563EB?logo=dotnet&logoColor=white" />
  <img alt="Firebase" src="https://img.shields.io/badge/Firebase-future-38BDF8?logo=firebase&logoColor=111827" />
</p>

---

## Engineering Workflow

| Practice | Purpose |
| --- | --- |
| GitFlow | Organize feature, release, and integration work across repositories. |
| Semantic Versioning | Communicate version intent clearly as the project evolves. |
| Conventional Commits | Keep commit history consistent and readable. |
| Pull Requests | Review changes before integration and document decisions. |
| Bounded Contexts | Keep business capabilities organized around domain concerns. |

Recommended commit style:

```text
feat(scope): add new capability
fix(scope): correct behavior
docs(scope): update documentation
refactor(scope): improve structure without changing behavior
```

---

## Academic Context

| Item | Detail |
| --- | --- |
| University | UPC |
| Course | Aplicaciones Web |
| Academic Cycle | 2026-10 |
| Team | Team King |
| Organization | `upc-pre-202610-1asi0730-12242-king` |

---

## Team

<table>
  <tr>
    <th align="left">Team</th>
    <th align="left">Focus</th>
  </tr>
  <tr>
    <td><strong>Team King</strong></td>
    <td>Nexa product design, web application development, platform planning, and academic documentation.</td>
  </tr>
</table>

---

<p align="center">
  <strong>Nexa</strong><br />
  Clean operational software for cold-chain coordination.
</p>
