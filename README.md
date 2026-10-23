# Kavay Khurana

**Java backend engineer** · Spring Boot · Spring Security · Spring AI · PostgreSQL
B.E. Computer Science & Engineering @ Thapar Institute of Engineering & Technology · Class of 2028

I build backends where AI gets real powers without being trusted blindly. The model can only *ask*: Spring Security decides, sensitive actions need a second human, and every decision lands in an audit log you can verify.

[![Portfolio](https://img.shields.io/badge/Portfolio-fortfolio--nine--dun.vercel.app-B9F25C?style=flat-square&logo=vercel&logoColor=black)](https://fortfolio-nine-dun.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-kavay--khurana-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kavay-khurana-437272322/)
[![LeetCode](https://img.shields.io/badge/LeetCode-530%2B_solved-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/kavaykhurana/)
[![Email](https://img.shields.io/badge/Email-kavaykhurana4%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:kavaykhurana4@gmail.com)

---

## Featured work

### [Warden](https://github.com/Kavaykhurana/warden) — permission-aware AI assistant · [live demo](https://warden-mauve.vercel.app)

`Java 21` `Spring Boot` `Spring Security` `Spring AI` `PostgreSQL` `React`

- The AI chooses from **14 backend actions**; Spring Security re-checks every one as the signed-in user, so even a prompt-injected model cannot exceed that user's rights.
- Grade changes and account deactivations need a **second approver**, enforced in code *and* by database constraints. Nobody approves their own request.
- **Hash-chained audit log** across 15 event types: alter or delete any past entry and the chain breaks.
- **135 unit and integration tests** (JUnit 5, Testcontainers), including a 56-case role × action authorization matrix, run on every build.

### [DocBuddy](https://github.com/Kavaykhurana/docbuddy) — document Q&A with page-level citations · [live demo](https://docbuddy-sgg1.onrender.com)

`Java 21` `Spring Boot` `Spring AI` `Spring Security` `PostgreSQL + pgvector` `React`

- Every answer links to the **exact page** it came from, so it can be verified in one click.
- **Hybrid retrieval**: semantic (pgvector) and keyword results fused with Reciprocal Rank Fusion in a single PostgreSQL query, catching exact terms like roll numbers and names that pure vector search misses.
- **No-answer path skips the LLM**: if your documents don't contain the answer, it says so instead of hallucinating one.
- Stateless JWT auth, no stored files, database-level per-user isolation and daily API-spend quotas. **68 tests** in CI.

### [Job-buddy](https://github.com/Kavaykhurana/Job-buddy) — academia–industry placement portal · [live demo](https://job-buddy-hs1e.onrender.com)

`Java 21` `Spring Boot 4` `Spring Data JPA` `PostgreSQL` `React` `Docker`

- Connects students, recruiters, institutions and academicians on one platform, matching on **assessed skills** instead of self-reported resumes.
- Recruiters compare each candidate's skills against job requirements and shortlist in one click; institutions get industry-demand data for curriculum planning.
- **Lead contributor** (38 of 60 commits, team of 3): built the Spring Boot 4 REST API (24 endpoints) and a single-container Docker deployment, live on Render with CI on every push.

---

## More I've built

| Project | What it is | Stack |
|---|---|---|
| **[Aureus AI](https://github.com/Kavaykhurana/Aureus_Ai)** · [live](https://aureus-ai-command-center.onrender.com) | Multi-agent financial intelligence platform. Five agents (analyst, risk, compliance, strategist, guardrail) work each query; a human must approve before any trade executes. | TypeScript, React, Express, SQLite, SSE |
| **[Tend](https://github.com/Kavaykhurana/tend)** | Family caregiving MCP server for Alexa+: medications, check-ins, appointments and family alerts, with an MCP Apps card and an Amazon Bedrock-driven Alexa+ simulator. | TypeScript, MCP SDK, Node, Amazon Bedrock |
| **[StockPilot](https://github.com/Kavaykhurana/EnterPrise_web_project)** · [live](https://stockpilot-on32.onrender.com) | Inventory, purchasing and sales management system with a transactional REST backend. | Java 21, Spring Boot, PostgreSQL |
| **[Enterprise CRM](https://github.com/Kavaykhurana/enterprise-crm)** | CRM backend built on Clean Architecture, DDD-lite and SOLID. | Java 21, Spring Boot, JPA, PostgreSQL |
| **[P51 MIA Audit](https://github.com/Kavaykhurana/p51-mia-audit)** | Membership-inference audit of CIFAR-10 classifiers: can an attacker tell whether an image was in your training set? Seven classifiers, shadow-model attacks. | Python |
| **[CodeBoard](https://github.com/Kavaykhurana/codeboard)** | Async code review for teams: submit snippets, assign reviewers, discuss in line-anchored threads. | JavaScript |

---

## Stack

| Area | Tools |
|---|---|
| **Languages** | Java · C++ · C · Python · JavaScript · TypeScript · SQL |
| **Backend** | Spring Boot · Spring Security · Spring AI · Spring Data JPA · Hibernate · REST · Microservices · Node.js · Express |
| **Security** | JWT · OAuth2 · Refresh-token rotation · BCrypt · RBAC |
| **Data** | PostgreSQL (+ pgvector) · MySQL · MongoDB · SQLite |
| **Testing** | JUnit 5 · Mockito · Testcontainers |
| **Infra & tools** | Docker · Maven · Git · GitHub · Render · Vercel · Railway |
| **Frontend** | React · Vite · Tailwind CSS |

---

## Also

- **530+ LeetCode problems** solved in C++ (115+ Medium) — [profile](https://leetcode.com/u/kavaykhurana/)
- **Anthropic certified:** [Claude Code in Action](https://verify.skilljar.com/c/3mk62fp7i24s) · [AI Fluency: Framework & Foundations](https://verify.skilljar.com/c/4rcwbfyvk3e7)
- **Now:** building secure, auditable AI systems on Spring · open to backend / SDE internships
