<!-- Profile README for ShadowAgents (Jason Vineis). -->

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:6366F1,100:06B6D4&text=Jason%20Vineis&fontSize=52&fontColor=ffffff&desc=AI%20Orchestration%20Systems%20Builder&descAlignY=67&animation=fadeIn"
    alt="Waving gradient hero banner with Jason Vineis and subtitle AI Orchestration Systems Builder"
  />
</p>

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=22&duration=2800&pause=900&center=true&vCenter=true&width=920&lines=I+build+reliable+fleets+of+AI+agents.;n8n+orchestration+-%3E+Supabase+brain+-%3E+governed+by+design.;Deterministic+first.+AI+second.+Approval-gated+always."
    alt="Animated typing headline describing reliable governed AI orchestration systems"
  />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-AI%20Agent%20Orchestration-6366F1?style=for-the-badge" alt="Focus badge: AI Agent Orchestration" />
  <img src="https://img.shields.io/badge/Stack-n8n%20%C2%B7%20Supabase%20%C2%B7%20Next.js-06B6D4?style=for-the-badge" alt="Stack badge: n8n, Supabase, Next.js" />
  <img src="https://img.shields.io/badge/Principle-Reliability%20%3E%20Cleverness-10B981?style=for-the-badge" alt="Principle badge: Reliability greater than Cleverness" />
</p>

## What I do

I design and operate reliable AI agent fleets - ~13 production agents across finance, rentals, documents, calendar, and email that coordinate to run real operations, not demos. Governed by design: deterministic logic first, AI second, with heartbeats, event logs, and human approval gates on every agent.

<p align="center">
  <img src="https://img.shields.io/badge/~13%20production%20agents-6366F1?style=for-the-badge" alt="Approximately 13 production agents" />
  <img src="https://img.shields.io/badge/n8n%20%E2%86%92%20Supabase%20%E2%86%92%20Lovable-06B6D4?style=for-the-badge" alt="n8n to Supabase to Lovable architecture" />
  <img src="https://img.shields.io/badge/Approval--gated%20by%20design-10B981?style=for-the-badge" alt="Approval gated by design" />
</p>

---

## Architecture

```mermaid
flowchart LR
    T([Triggers: schedule, webhook, chat]) --> N[n8n - logic and orchestration]
    N -- writes --> S[(Supabase - source of truth)]
    S -- reads --> L[Lovable - read-only dashboards]
    N -. heartbeats .-> H[workflow_health]
    N -. actions .-> E[agent_events]
    N -- destructive? --> A{approval_requests}
    A -- approved by human --> N
    subgraph Fleet[Agent Fleet]
      C[chief_of_staff]
      R[rental_intelligence]
      F[finance_intelligence]
      D[document_intelligence]
      G[gmail_intelligence]
    end
    C -.coordinates.- R & F & D & G
    N --- Fleet
    classDef brain fill:#06B6D4,stroke:#0891B2,color:#fff
    classDef logic fill:#6366F1,stroke:#4F46E5,color:#fff
    class S brain
    class N,C logic
```

---

## See it run

[![Watch the demo](https://img.shields.io/badge/%E2%96%B6%20Watch%20the%20demo-FF0033?style=for-the-badge)](https://example.com/demo)

<!-- Demo options: 1) Add a GIF at assets/demo.gif and replace the badge above with: ![JasonOS demo](assets/demo.gif)  2) Or drag-drop an MP4 directly into this README in the GitHub editor and GitHub will render a native video player. -->

---

## How approvals work

<details>
  <summary><strong>Proof-of-governance audit trail (sanitized example)</strong></summary>

- `approval_request` created for a destructive-action candidate
- Human reviewer approves the request
- Action executes through the orchestrated workflow
- `agent_events` records the action metadata
- `workflow_health` receives the updated heartbeat state

</details>

---

## Tech toolbox

<p>
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Next.js-111111?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Anthropic_Claude-191919?style=flat-square&logo=anthropic&logoColor=white" alt="Anthropic Claude" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram" />
</p>

---

## Roadmap

```mermaid
timeline
    title Good / Better / Best rollout
    Q3 : Rental OS SKU #1
    Q4 : Finance Intelligence rollout
    Q1 : Document Intelligence rollout
    Q2 : Full composable Good/Better/Best menu
```

---

## How I'd build yours in 30 days

1. **Discover** - map one high-friction operational workflow worth automating.
2. **Build** - ship one governed, approval-gated agent into production.
3. **Prove** - measure reliability, speed, and decision quality on real operations.

[![Book a call](https://img.shields.io/badge/Book%20a%20Call-6366F1?style=for-the-badge)](https://example.com/book-a-call)

---

## Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ShadowAgents&count_private=true&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub activity stats for ShadowAgents" />
</p>

---

## Contact

[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:{{EMAIL}})
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)]({{LINKEDIN_URL}})

<p align="center"><sub><em>Reliability beats cleverness. Simplicity beats over-engineering.</em></sub></p>

<!-- STAGED TODO (invisible by design):
  #1 Live fleet-status dynamic badge from public sanitized JSON
  #2 Self-updating README via GitHub Action markers
  #6 Self-hosted animated SVG hero (light/dark variants)
  #7 Custom KPI SVG card sourced from public sanitized metrics
-->
