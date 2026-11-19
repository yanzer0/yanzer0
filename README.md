<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:020202,100:143A31&height=180&section=header&text=&fontSize=0" width="100%" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/lockup-horizontal-onyx.svg">
  <img src="assets/lockup-horizontal-light.svg" alt="Infuser" height="64">
</picture>

<br/><br/>

**Yan Galasso** · Founder @ Infuser<br/>
I build AI systems that run inside B2B operations · São Paulo, Brazil

<br/>

<a href="https://useinfuser.com"><img src="https://img.shields.io/badge/useinfuser.com-C6FF34?style=for-the-badge&logoColor=000" /></a>
<a href="https://www.linkedin.com/in/yangalasso/"><img src="https://img.shields.io/badge/LinkedIn-171717?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://instagram.com/yangalasso"><img src="https://img.shields.io/badge/@yangalasso-171717?style=for-the-badge&logo=instagram&logoColor=white" /></a>
<a href="mailto:yangalasso@useinfuser.com"><img src="https://img.shields.io/badge/Email-171717?style=for-the-badge&logo=gmail&logoColor=white" /></a>

</div>

<br/>

## What I do

Infuser puts AI to work inside B2B companies. I lead the technical side: I write the systems, the integrations and the agents, and I work with operations in Brazil and the US, in fields like law, healthcare, distribution and automotive.

Most of it is private because it runs on client data. The contribution graph on this profile is the public trace of that work. What I can show here is how we approach a process, how the systems are built, and the products we sell openly.

<br/>

## Look before you automate

We call it the Catalyst Protocol. Automating a process nobody has mapped only makes its waste run faster, and what people say they do is often not what they do. So before we build anything, we watch a real case, start to finish, with the person who does it every day. What shows up on screen counts as measured. What is only said stays marked as an estimate.

<p align="center"><img src="assets/catalyst-protocol-flow.png" alt="Catalyst Protocol flow" width="100%"></p>

The client ends up with a map of how the process runs today, a proposed flow, a ranked list of opportunities and a plan to compare before and after. Nothing replaces the current way of working until the new one has been tested side by side.

<br/>

## How it is built

The core is a multi-tenant MCP server in Node.js and TypeScript, and client businesses run on it. The parts I care about most are not the framework:

- Each client is an isolated tenant, encrypted at rest, and access is granted by area, so HR does not see finance.
- Every tool call is audited, and documents are versioned with optimistic locking, so nothing gets silently overwritten.
- Where a system has no API, a scheduled browser worker operates it, and it stops to ask a person when a value looks off.
- Every run reports back what happened, with the result one click away.

On top of that sits an ops panel with a conversational second brain over the company's approved sources, and a work screen per routine with an owner, the human decisions and a way out for exceptions.

<br/>

## Products

Client systems are private. What is public is what we also sell at [useinfuser.com](https://useinfuser.com), where prices and details live:

| Product | What it is |
|---|---|
| Kit Segundo Cérebro | Gives Claude Code memory across sessions |
| A Legião | 80 specialist agents for copy, traffic, sales and offers |
| Estúdio de CrIAção | 12 agents for video creation and editing |
| Kit de Skills | 10 skills that turn Claude Code into a team |
| JARVIS Kit | Apps and routines triggered by claps or voice |

There is also a free Central with 67 guides and packages, from the first prompt to the first agent running.

<br/>

## Panels

Screens from the Painel OS, the panel our clients work in. The files screen comes from our test environment.

<p><img src="assets/painel-clinica-predio.jpg" alt="Agents map" width="100%"><br><sub><b>Agents map.</b> Everything the company has, by area, marked as live, coming soon or on request.</sub></p>

<p><img src="assets/painel-saas-arquivos-hover.jpg" alt="Files" width="100%"><br><sub><b>Files.</b> Originals organized by folder, always within reach.</sub></p>

<!-- DECISION (Yan): three more prints are hidden (agents, one agent flow, run result). They show a client name, a client location and third-party system names. Clause 8 of the Auto Select contract allows a public mention only after prior validation of the content by the client and without operational data. Restore them only after Hercilio approves the content. Files are in C:\tmp\readme-prints. -->
<br/>

## Stack

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-171717?style=for-the-badge&logo=typescript&logoColor=3178C6)
![Node.js](https://img.shields.io/badge/Node.js-171717?style=for-the-badge&logo=nodedotjs&logoColor=5FA04E)
![React](https://img.shields.io/badge/React-171717?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-171717?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-171717?style=for-the-badge&logo=vite&logoColor=FFD62E)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-171717?style=for-the-badge&logo=tailwindcss&logoColor=06B6D4)
![SQLite](https://img.shields.io/badge/SQLite-171717?style=for-the-badge&logo=sqlite&logoColor=66B5E0)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-171717?style=for-the-badge&logo=postgresql&logoColor=4169E1)
![n8n](https://img.shields.io/badge/n8n-171717?style=for-the-badge&logo=n8n&logoColor=EA4B71)
![Playwright](https://img.shields.io/badge/Playwright-171717?style=for-the-badge&logo=playwright&logoColor=2EAD33)
![Docker](https://img.shields.io/badge/Docker-171717?style=for-the-badge&logo=docker&logoColor=2496ED)
![Caddy](https://img.shields.io/badge/Caddy-171717?style=for-the-badge&logo=caddy&logoColor=1F88C0)
![Claude Code](https://img.shields.io/badge/Claude_Code-171717?style=for-the-badge&logo=claude&logoColor=D97757)
![Codex](https://img.shields.io/badge/Codex-171717?style=for-the-badge&logo=openai&logoColor=white)

MCP (Model Context Protocol) · Tailscale · Backblaze B2

If you run a B2B operation and want to see where AI fits, start at [useinfuser.com](https://useinfuser.com).

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:020202,100:143A31&height=100&section=footer" width="100%" />

</div>