<h1 align="center">Pranav Govind</h1>

<p align="center">
<b>Co-founder &amp; CTO · ZyFolks Technologies</b><br>
Kozhikode, India
</p>

<p align="center">
<a href="https://prgofficial.me">prgofficial.me</a>
&nbsp;·&nbsp;
<a href="https://zyfolks.com">zyfolks.com</a>
&nbsp;·&nbsp;
<a href="https://linkedin.com/in/prgofficial">linkedin</a>
&nbsp;·&nbsp;
<a href="mailto:prg@zyfolks.com">email</a>
</p>

<br>

> I build software where product decisions, engineering, and systems design meet.

My work spans product architecture, application engineering, AI systems, and infrastructure. I care about building things that are straightforward to operate, deliberate in their trade-offs, and useful beyond the first release.

My background is in mechanical engineering, graduating in 2019. I moved into software development in 2021 and have since worked across product development, technical leadership, and early-stage software systems.

<br>

## What I work on

**Product engineering**
Taking products from an idea or requirement to a working system, with attention to architecture, implementation, and the decisions that become expensive later.

**AI systems**
AI-assisted products, integrations, workflows, evaluation, and the surrounding infrastructure required to make them dependable.

**Application architecture**
APIs, multi-tenant systems, databases, authentication, integrations, background processing, and the less visible parts that make software hold together.

**Web3**
Smart contracts, wallet integrations, on-chain interactions, and applications built around blockchain infrastructure.

<br>

## Selected work

Most of my production work is private. A few public projects are below.

| Project                                                                     | Description                                                                                                         |
| --------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| **[Zybo AI](https://zyfolks.com/demo/zybo-ai/)**                            | AI support system grounded in a company's own documentation, with human escalation when confidence is low.          |
| **[AI Blockchain Explorer](https://zyfolks.com/demo/blockchain-explorer/)** | Natural-language exploration of wallets and on-chain activity across multiple networks.                             |
| **[Content Studio](https://zyfolks.com/demo/content-studio/)**              | Research, drafting, source validation, and human review brought into a single AI-assisted workflow.                 |
| **[AI Virtual Try-On](https://zyfolks.com/demo/virtual-try-on/)**           | Image-generation based virtual try-on that generates the garment onto the subject rather than simply overlaying it. |
| **[Web3 Dapps](https://zyfolks.com/demo/web3-dapps/)**                      | Decentralized applications combining smart contracts, wallet connectivity, and on-chain logic.                      |
| **[OperationsHub](https://zyfolks.com/demo/operations-hub/)**               | Internal business platform covering CRM, invoicing, approvals, and reporting.                                       |
| **[eCommerce Platform](https://zyfolks.com/demo/ecommerce-platform/)**      | Commerce platform covering catalogues, payments, orders, and fulfilment workflows.                                  |

<br>

## Open source

### [ai-footprint](https://github.com/prgofficial/ai-footprint)

A local-first analytics tool for understanding how AI coding assistants are used across projects.

It reads locally stored coding-assistant transcripts and turns them into analytics around projects, activity, and usage. The data comes from the user's own events rather than sample or synthetic data.

One of the core design constraints is privacy:

> **The application makes no outbound network calls.**

There is no account, API key, or telemetry. The test suite patches the socket layer and runs the full pipeline — ingestion, enrichment, aggregation, and export — failing the build if anything attempts to connect outside the machine.

```bash
git clone https://github.com/prgofficial/ai-footprint
cd ai-footprint
sh init.sh
```

<p align="center">
<sub>
TypeScript · NestJS · React · SQLite / FTS5 · Docker · Node.js 20+ · MIT
</sub>
</p>

<br>

## Technology

<table>
<tr>
<td valign="top" width="33%">

**Languages**

TypeScript
Python
JavaScript
Solidity

</td>

<td valign="top" width="33%">

**Application**

Node.js
NestJS
React
Astro
Laravel

</td>

<td valign="top" width="33%">

**Infrastructure**

PostgreSQL
SQLite
Docker
AWS
GitHub Actions

</td>
</tr>
</table>

<br>

## Principles

I generally prefer:

`simple systems` over unnecessary abstraction

`boring infrastructure` over complexity for its own sake

`measurable behaviour` over assumptions

`good defaults` over configuration everywhere

`shipping` over endlessly polishing the plan

<br>

---

<p align="center">
<samp>
<a href="https://prgofficial.me">prgofficial.me</a>
&nbsp;·&nbsp;
<a href="https://linkedin.com/in/prgofficial">LinkedIn</a>
&nbsp;·&nbsp;
<a href="mailto:prg@zyfolks.com">prg@zyfolks.com</a>
</samp>
</p>
