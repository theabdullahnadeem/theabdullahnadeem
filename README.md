<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=220&section=header&text=Abdullah%20Nadeem&fontSize=52&fontColor=e0aaff&animation=fadeIn&fontAlignY=38&desc=Full%20Stack%20Developer%20%7C%20Founder%20%40%20Digivixo&descAlignY=58&descSize=18" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=C77DFF&center=true&vCenter=true&width=600&lines=Full+Stack+Developer;Building+MEET-AI+%7C+Real-Time+Systems;Founder+%40+Digivixo;TypeScript+%2F+Next.js+%2F+Node.js" alt="Typing SVG" />
</a>

<br/>

![BSCS Student](https://img.shields.io/badge/BSCS-Virtual%20University-6a0dad?style=flat-square&logo=readthedocs&logoColor=white)
![Location](https://img.shields.io/badge/Location-Lahore%2C%20Pakistan-6a0dad?style=flat-square&logo=googlemaps&logoColor=white)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-abdullahpk.site-7B2CBF?style=for-the-badge&logo=vercel&logoColor=white)](https://abdullahpk.site)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-5A189A?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdullah-nadeem-319560285)
[![Email](https://img.shields.io/badge/Email-Contact-3C096C?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abdullahnadeem2580@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-240046?style=for-the-badge&logo=github&logoColor=white)](https://github.com/theabdullahnadeem)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=theabdullahnadeem&color=7b2cbf&style=flat-square&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/theabdullahnadeem?color=9d4edd&style=flat-square&label=Followers)
![Stars](https://img.shields.io/github/stars/theabdullahnadeem?color=c77dff&style=flat-square&label=Stars)

</div>

---

## About

Full stack developer working across the modern TypeScript stack — Next.js, Node.js, PostgreSQL — with a focus on real-time systems, multi-tenant architecture, and payment infrastructure that has to hold up under actual production load, not just demo conditions.

Currently building **MEET-AI**, a real-time AI meeting platform on a LiveKit-based stack (tRPC, Inngest, Drizzle/Postgres), following a full migration off GetStream. Also founder of **Digivixo**, an AI automation agency building white-label voice and workflow automation for US/UK accounting firms.

I care more about whether a system holds up under concurrent users and edge cases than whether it looks good in a screenshot. Currently a BSCS student at Virtual University of Pakistan, balancing coursework with production client work.

**Open To:**
- Full-time / contract full stack engineering roles (remote-first)
- Backend and real-time systems work
- Freelance builds involving payments, auth, or multi-tenant architecture

---

## Tech Stack

**Languages**

![TypeScript](https://skillicons.dev/icons?i=ts) ![JavaScript](https://skillicons.dev/icons?i=js) ![Python](https://skillicons.dev/icons?i=py) ![C++](https://skillicons.dev/icons?i=cpp) ![SQL](https://skillicons.dev/icons?i=postgres)

**Frontend**

![React](https://skillicons.dev/icons?i=react) ![Next.js](https://skillicons.dev/icons?i=next) ![Tailwind](https://skillicons.dev/icons?i=tailwind) ![HTML5](https://skillicons.dev/icons?i=html) ![CSS3](https://skillicons.dev/icons?i=css)

**Backend & Databases**

![Node.js](https://skillicons.dev/icons?i=nodejs) ![PostgreSQL](https://skillicons.dev/icons?i=postgres) ![Redis](https://skillicons.dev/icons?i=redis) ![Supabase](https://skillicons.dev/icons?i=supabase)

**Cloud, DevOps & Tooling**

![Git](https://skillicons.dev/icons?i=git) ![GitHub](https://skillicons.dev/icons?i=github) ![Docker](https://skillicons.dev/icons?i=docker) ![Vercel](https://skillicons.dev/icons?i=vercel) ![Postman](https://skillicons.dev/icons?i=postman)

---

## Featured Projects

<details>
<summary><b>MEET-AI — Real-Time AI Meeting Platform</b></summary>
<br/>

AI-powered meeting platform with real-time transcription, note-taking, and structured meeting intelligence — built to compete on the specific gaps in tools like Fathom and Fireflies. Migrated from GetStream to a LiveKit-based real-time stack.

| | |
|---|---|
| **Stack** | Next.js, TypeScript, tRPC, Inngest, Drizzle ORM, PostgreSQL, LiveKit, OpenAI Realtime API |
| **Scale** | Real-time multi-participant sessions with concurrent audio/transcription pipelines |
| **Performance** | Event-driven background jobs via Inngest for async processing off the request path |
| **Security** | Type-safe API layer via tRPC, environment-isolated secrets |
| **Impact** | Core product in active development; positioned against Fathom / Fireflies |
| **Repository** | [github.com/theabdullahnadeem](https://github.com/theabdullahnadeem) |

Handles the coordination problem behind real-time meeting tooling: keeping transcription, session state, and background AI processing in sync without blocking the live session. The GetStream-to-LiveKit migration was a full SDK swap, not a wrapper — session handling, event architecture, and real-time data flow were rebuilt.

</details>

<details>
<summary><b>Fraviont Store — Multi-Gateway E-Commerce Platform</b></summary>
<br/>

Production e-commerce build for a real client, supporting multiple regional payment gateways so checkout doesn't break depending on where the buyer is paying from.

| | |
|---|---|
| **Stack** | Next.js, TypeScript, Stripe, JazzCash, PayFast |
| **Scale** | Multi-gateway checkout supporting international and regional payment methods |
| **Performance** | GSAP-driven animated storefront without sacrificing checkout speed |
| **Security** | Isolated payment gateway integrations, no card data touching app servers |
| **Impact** | Live client project, in production use |
| **Repository** | [github.com/theabdullahnadeem](https://github.com/theabdullahnadeem) |

The hard part wasn't the storefront — it was making three payment providers with different APIs, currencies, and failure modes behave consistently at checkout.

</details>

<details>
<summary><b>Vettely — Multi-Tenant Recruitment Automation SaaS</b></summary>
<br/>

End-to-end recruitment SaaS with AI-driven candidate screening and voice interviews, built for multi-tenant organizations from the ground up.

| | |
|---|---|
| **Stack** | Next.js App Router, Groq (Llama 3.3 70B), Supabase, Better Auth (org plugin), Vapi, Lemon Squeezy |
| **Scale** | Multi-tenant architecture with organization-level data isolation |
| **Performance** | LLM-backed screening pipeline via Groq for low-latency inference |
| **Security** | Better Auth with org-scoped permissions and billing tied to Lemon Squeezy |
| **Impact** | In active development — not yet in production |
| **Repository** | [github.com/theabdullahnadeem](https://github.com/theabdullahnadeem) |

> **Status:** Currently in development. Architecture and documentation are complete; not yet shipped to production.

</details>

<details>
<summary><b>PakTechJobs — Real-Time Job Board</b></summary>
<br/>

Job board platform built to handle real-time updates at scale using pub/sub architecture rather than naive polling.

| | |
|---|---|
| **Stack** | Next.js, TypeScript, Node.js, Redis, WebSockets |
| **Scale** | Multi-instance WebSocket scaling via Redis pub/sub |
| **Performance** | Real-time updates without per-client polling overhead |
| **Security** | Standard auth and session handling across distributed instances |
| **Impact** | Portfolio-anchoring project demonstrating distributed real-time architecture |
| **Repository** | [github.com/theabdullahnadeem](https://github.com/theabdullahnadeem) |

The interesting engineering problem here is horizontal scaling of WebSocket connections — a single-instance WebSocket server doesn't scale, and Redis pub/sub is the standard fix.

</details>

---

## Experience

**Full Stack Developer** — The Soft Biz
`July 2025 — Present`

Full stack development role covering production client work across the modern JS/TS stack.

- Building and maintaining full stack applications end-to-end
- Working across frontend, backend, and database layers
- Collaborating on client-facing production systems

`TypeScript` `Next.js` `Node.js` `PostgreSQL`

<br/>

**Full Stack Developer (Part-Time)** — Arfa Karim Technology
`February 2024 — May 2025`

Part-time full stack development role while completing BSCS coursework.

- Contributed to full stack feature development
- Worked within an existing production codebase and team workflow

`JavaScript` `React` `Node.js`

<br/>

**CEO & Co-Founder** — Digivixo
`Ongoing`

AI automation agency building white-label voice and workflow automation for US/UK CPA and accounting firms. Currently in pre-revenue client acquisition.

- Leading product direction for white-label AI voice receptionist offering
- Evaluated and selected AI voice infrastructure (OmniDimension) after eliminating Retell and Vapi on white-label capability grounds
- Running outbound client acquisition via Apollo.io and direct outreach

`Product Strategy` `AI Voice Infrastructure` `B2B Sales` `Outbound`

---

## Achievements

<div align="center">

| Recognition | Details |
|---|---|
| GetStream → LiveKit Migration | Full real-time SDK migration on MEET-AI without service interruption to architecture |
| Multi-Gateway Payment Integration | Shipped production checkout across Stripe, JazzCash, and PayFast for Fraviont Store |
| Distributed Real-Time Architecture | Designed Redis pub/sub WebSocket scaling for PakTechJobs |
| Founder, Digivixo | Built and led an AI automation agency from zero to active client acquisition |

</div>

---

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=theabdullahnadeem&show_icons=true&theme=radical&hide_border=true&bg_color=0d0221&title_color=c77dff&icon_color=9d4edd&text_color=e0aaff" width="48%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=theabdullahnadeem&theme=radical&hide_border=true&background=0d0221&stroke=9d4edd&ring=c77dff&fire=e0aaff" width="48%" />

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=theabdullahnadeem&layout=compact&theme=radical&hide_border=true&bg_color=0d0221&title_color=c77dff&text_color=e0aaff" width="48%" />

</div>

---

## GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=theabdullahnadeem&theme=radical&no-frame=true&column=4&margin-w=10&margin-h=10" />

</div>

---

## Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=theabdullahnadeem&theme=react-dark&bg_color=0d0221&color=c77dff&line=9d4edd&point=e0aaff&hide_border=true" width="100%" />

</div>

---

## Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/theabdullahnadeem/theabdullahnadeem/output/github-contribution-grid-snake-dark.svg" width="100%" />

</div>

> Snake animation requires a GitHub Actions workflow (`platane/snk`) configured on the profile repo to generate `github-contribution-grid-snake-dark.svg`. If not yet set up, this section will render as a broken image until that workflow runs once.

---

## Current Focus

```yaml
current_focus:
  learning:
    - Advanced real-time system design patterns
    - Distributed systems at scale
  building:
    - MEET-AI: LiveKit-based real-time AI meeting platform
    - Digivixo: white-label AI voice automation for CPA firms
  exploring:
    - AI voice infrastructure (OmniDimension) for white-label deployment
    - Multi-tenant SaaS architecture patterns
  open_to:
    - Full-time / contract full stack roles
    - Backend and real-time systems engineering
    - Freelance work involving payments, auth, or multi-tenant systems
```

---

## Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-abdullahnadeem2580%40gmail.com-3C096C?style=flat-square&logo=gmail&logoColor=white)](mailto:abdullahnadeem2580@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-abdullah--nadeem-5A189A?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdullah-nadeem-319560285)
[![GitHub](https://img.shields.io/badge/GitHub-theabdullahnadeem-240046?style=flat-square&logo=github&logoColor=white)](https://github.com/theabdullahnadeem)
[![Portfolio](https://img.shields.io/badge/Portfolio-abdullahpk.site-7B2CBF?style=flat-square&logo=vercel&logoColor=white)](https://abdullahpk.site)

</div>

---

<div align="center">

*Code that holds up under real load matters more than code that looks good in a demo.*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" />

</div>
