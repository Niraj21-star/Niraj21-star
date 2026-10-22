<!-- NIRAJ KARNAWAT — GITHUB PROFILE README · "Workbench" design -->

<div align="center">

<samp>N / K</samp>

<h1>Hey, I’m Niraj.</h1>

<h3>I like understanding how things work — and building things that make them work better.</h3>

<strong>AI &amp; Data Science Engineering Student</strong>

<p>B.E. Artificial Intelligence &amp; Data Science · Dr. D. Y. Patil Institute of Technology, Pune (SPPU) · Class of 2028<br />CGPA 9.45/10 — Department Topper · Co-founder, Solvora (AyuSync) · Web &amp; App Development Lead, GDG DIT Pimpri</p>

<p><code>AI systems</code> · <code>Software engineering</code> · <code>Curious experiments</code></p>

<br />

<samp>● CURRENTLY BUILDING &nbsp;&nbsp; / &nbsp;&nbsp; SHIP SMALL. LEARN LOTS.</samp>

<br /><br />

<a href="#02--projects-from-the-workbench">Projects</a> &nbsp;·&nbsp;
<a href="#03--tools-i-reach-for">Toolkit</a> &nbsp;·&nbsp;
<a href="#04--notes-from-the-workbench">Notes</a> &nbsp;·&nbsp;
<a href="#05--have-an-interesting-problem-to-solve">Contact</a>

</div>

---

<pre align="center">
┌─────────────────────────── curiosity.ts ───────────────────────────┐
│                                                                    │
│  const workbench = {                                               │
│    question:  "How does this really work?",                        │
│    method:    ["build", "test", "trace", "improve"],               │
│    direction: "useful software + dependable AI systems"            │
│  };                                                                │
│                                                     _              │
│  $ learn --by-doing                               _|=|__________    │
│  → one small commit at a time                    /  ..........  \   │
│  █                                               \____________/    │
│                                                                    │
└────────────────────────────────────────────────────────────────────┘
</pre>

## 01 — Curious about the details.

I learn best by building the thing, breaking it gently, and tracing how the
pieces connect.

My work sits where **AI engineering** and **software development** meet. I care
about useful interfaces, dependable systems, and understanding the decisions
hidden behind the final product.

In practice, that means shipping for real users: through **Solvora (AyuSync)** — my freelance
product practice — I built a **production school ERP** for a live institutional client, and I lead
web & app development for **GDG DIT Pimpri**, a 500+ member developer community.

<p>
  <kbd>AI engineering</kbd>&nbsp;
  <kbd>Full-stack development</kbd>&nbsp;
  <kbd>Developer tools</kbd>&nbsp;
  <kbd>Reliable AI agents</kbd>&nbsp;
  <kbd>Open source</kbd>
</p>

> **Workbench note:** keep digging until the abstraction makes sense.

---

## 02 — Projects from the workbench.

Things I have designed, built, and shipped — a production system running at a real
school, safer AI, and better ways to learn.

<table>
<tr>
<td width="50%" valign="top">

<samp>PROJECT / 01 · PRODUCTION · LIVE SINCE SEP 2025</samp>

<h3>Solvora School ERP</h3>

<strong>School management, running at a real institution</strong>

<p>Admissions, fees, and daily administration digitised end to end for a live
client — 700+ admissions, 12+ daily users, and automated document generation
that replaced 4–5 hours of manual work every day.</p>

<pre>
admissions ──> fees ──> records
     │                      │
     └── auto-generated ────┘
         forms + certificates
</pre>

<p>
<code>Node.js</code> <code>Express</code> <code>MongoDB</code><br />
<code>React</code> <code>Puppeteer</code> <code>REST APIs</code>
</p>

<samp>CLIENT SYSTEM — WALKTHROUGH ON REQUEST</samp>

</td>
<td width="50%" valign="top">

<samp>PROJECT / 02 · SPECIAL RECOGNITION · INFOSYS IGNITE 2026</samp>

<h3><a href="https://github.com/Niraj21-star/guard_ai">GuardRail</a></h3>

<strong>AI agent security and action guardrails</strong>

<p>Evaluating proposed AI agent actions before execution — authorization,
reversibility, and impact. Validated against a 42-attack adversarial benchmark,
with a tamper-evident SHA-256 audit log.</p>

<pre>
proposed action
      │
      ├── authorization ──┐
      ├── reversibility ──┼──> policy check ──> allow / block
      └── impact ─────────┘
</pre>

<p>
<code>Policy evaluation</code> <code>Deterministic enforcement</code><br />
<code>Risk classification</code> <code>Python</code>
</p>

<samp>REPOSITORY — <a href="https://github.com/Niraj21-star/guard_ai">github.com/Niraj21-star/guard_ai</a></samp>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<samp>PROJECT / 03 · BUILT &amp; SHIPPED</samp>

<h3><a href="https://github.com/Niraj21-star/Learnloop">LearnLoop AI</a></h3>

<strong>Adaptive learning and assessment</strong>

<p>Personalises what a learner studies next using Bayesian Knowledge Tracing
over a prerequisite graph — with a Monaco coding workspace, a sandboxed Docker
code runner, and instructor analytics.</p>

<pre>
foundations ──> practice ──> assess
      ^                         │
      └──── adapt next step <───┘
</pre>

<p>
<code>Learning progress</code> <code>Adaptive assessment</code><br />
<code>Next.js</code> <code>TypeScript</code> <code>PostgreSQL</code>
</p>

<samp>REPOSITORY — <a href="https://github.com/Niraj21-star/Learnloop">github.com/Niraj21-star/Learnloop</a></samp>

</td>
<td width="50%" valign="top">

<samp>PROJECT / 04 · FULL-STACK BUILD</samp>

<h3><a href="https://github.com/Niraj21-star/nexconnect">NexConnect</a></h3>

<strong>Professional networking, with trust built in</strong>

<p>A professional platform with multi-factor identity verification, company
ownership validation, and a dynamic Trust Engine that scores trust in real
time from verification signals and behaviour.</p>

<pre>
verification ──┐
               ├──> trust engine ──> trust score
behaviour ─────┘
</pre>

<p>
<code>Next.js</code> <code>TypeScript</code><br />
<code>MongoDB</code> <code>Better Auth</code> <code>REST APIs</code>
</p>

<samp>REPOSITORY — <a href="https://github.com/Niraj21-star/nexconnect">github.com/Niraj21-star/nexconnect</a></samp>

</td>
</tr>
</table>

---

## 03 — Tools I reach for.

An evolving stack selected by what the project needs—not collected for a badge
wall.

| 01 / Languages | 02 / Frontend + backend |
| --- | --- |
| `Python` · `TypeScript` · `JavaScript` · `SQL` | `React` · `Next.js` · `Node.js` · `Express` · `FastAPI` · `Tailwind CSS` |

| 03 / Data + infrastructure | 04 / Developer tools |
| --- | --- |
| `PostgreSQL` · `MongoDB` · `MySQL` · `Docker` · `AWS` | `Git` · `GitHub` · `Vercel` · `CI/CD` |

<sub>← always learning the layer underneath</sub>

---

## 04 — Notes from the workbench.

Small starting points for experiments, open-source discoveries, and lessons
worth sharing.

<details>
<summary><strong>NOTE_01 / Where should an AI agent stop?</strong></summary>
<br />
Thinking about authorization, reversibility, and impact before an action reaches
the real world.
<br /><br />
<samp>TOPIC · AI AGENT SAFETY</samp>
</details>

<details>
<summary><strong>NOTE_02 / Learning by shipping the smallest useful version.</strong></summary>
<br />
A workbench note on narrowing scope without losing the interesting engineering
question.
<br /><br />
<samp>TOPIC · BUILDING IN PUBLIC</samp>
</details>

<details>
<summary><strong>NOTE_03 / Tools should explain themselves.</strong></summary>
<br />
Exploring developer interfaces that make system state, errors, and trade-offs
easier to see.
<br /><br />
<samp>TOPIC · DEVELOPER TOOLING</samp>
</details>

<br />

```text
□ □ ■ □ □ □ □   □ ■ □ □ □ □ □   □ □ □ ■ □ □ □
□ ■ □ □ □ □ □   □ □ □ □ ■ □ □   ■ □ □ □ □ □ □
```

<sub>Consistency over streaks. This motif is decorative and does not represent contribution statistics.</sub>

---

## 05 — Have an interesting problem to solve?

Always happy to talk about useful software, AI systems, open source, or an
interesting engineering challenge.

<samp>● OPEN TO SWE · APPLIED AI · FORWARD DEPLOYED ENGINEER INTERNSHIPS FROM NOV 2026 &nbsp;/&nbsp; PUNE · REMOTE · BENGALURU</samp>

| Find me | Verified detail |
| --- | --- |
| **GitHub** | [github.com/Niraj21-star](https://github.com/Niraj21-star) |
| **LinkedIn** | [linkedin.com/in/niraj-karnawat-0243ba308](https://www.linkedin.com/in/niraj-karnawat-0243ba308) |
| **Email** | [karnawatniraj@gmail.com](mailto:karnawatniraj@gmail.com) |
| **Portfolio** | [nirajskarnawat.in](https://nirajskarnawat.in) |


<br />

<div align="center">

<samp>N / K &nbsp;·&nbsp; MADE WITH CURIOSITY &nbsp;·&nbsp; &gt;_</samp>

</div>
