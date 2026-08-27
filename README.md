# Dongyeong Jeong (정동영)

<a href="https://www.linkedin.com/in/yeongj/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

> **Full-Stack Product Engineer with a frontend focus**

I build web and mobile products with React, TypeScript, and Flutter, and extend into Django and Spring Boot when a product problem crosses API, data, admin, or release boundaries.

## Experience

### EduU Learning · Software Engineer

- **Contract / Freelance Developer** · `2025–2026` · Approximately 8–9 months in total
- **Software Engineer Intern** · `2026.07–2026.08`

Started as a freelance developer and later accepted an on-site internship offer from the same company; the roles overlapped during `2026.07–2026.08`.

During the internship, worked on **CoTeacher, OU, and SYM**. Across the freelance and internship engagements, work spanned React/Next.js user and admin interfaces, Flutter/Expo mobile flows, Django/Spring Boot API contracts, QA, and release validation—including payment recovery and operator tooling for OU.

The company repositories are non-public; the links below point to live services. The descriptions distinguish work I implemented, verified, or reviewed.

## Selected products

### [CoTeacher](https://web.coteacher.net) · Financial education platform

`Next.js` · `React` · `TypeScript` · `Django` · `PostgreSQL`

- Implemented and verified content, payment, review-queue, and error-state flows across the React/Next.js user web, Flutter mobile app, React admin, and Django API.
- On a 100-course synthetic fixture, reduced catalog query count from **202 to 2** and added regression coverage; verified Django 5.2 LTS compatibility by running the existing **8,210-test backend suite**.

### [SYM · 이지언어](https://xn--oh5bh54khzd.com) · Education operations platform

`React` · `TypeScript` · `Spring Boot` · `PostgreSQL` · `Expo`

- Implemented attendance and student-management flows across React/Expo clients and Spring APIs; kept domain writes and outbox registration in one transaction, then moved notification delivery to a retryable worker.
- During peer review, identified preview/commit snapshot drift, inconsistent season-to-student lock ordering, and a missing history-endpoint authorization guard; re-reviewed the fixes before approval.

## Additional Projects

- **Filient** · SW Maestro 16th Cohort · AI-powered macOS file automation<br>
  Built Flutter rule, history, and rollback flows; added macOS integration, localization, and product guides.<br>
  [Product website](https://filient.ai) · [App repository](https://github.com/BlueGreenSWM/Filient_MVP_2) · [Web repository](https://github.com/BlueGreenSWM/Filient_Homepage)
- **Bridge** · 2026 GDGoC quadS Hackathon, General Track · Parent–child digital usage management<br>
  Built role-specific flows across two Flutter apps and aligned time, mission, and notification contracts with Spring APIs.<br>
  [Parent app](https://github.com/2026-quadS-Bridge-Project/Quad-S-Team12-App-Parent) · [Child app](https://github.com/2026-quadS-Bridge-Project/Quad-S-Team12-App-Child) · [API](https://github.com/2026-quadS-Bridge-Project/2026-Bridge-quadS)

## Education

- [**SeoulTech ITM**](https://itm.seoultech.ac.kr/en/about/intro) · `2020.03–2027.02 (Expected)` · Dual degree with **Northumbria University**

## Programs & Activities

### Programs

- **SW Maestro · 16th Cohort** · `2025.04–2025.12` · Completed
- [**Promising Student Startup Team 300+ (U300+)**](https://u300.kr/about/u300) · Growth Track · `2026–Present`

### Teaching

- **Coding Education Assistant Instructor** · Samsung Dream Scholarship Foundation-linked program · `2026.05–Present`<br>
  Supported coding education for middle and high school students.
- **AI Startup Education PBL Instructor** · AI School Up, AND Center · `2026.06–2026.08`<br>
  Led project-based AI entrepreneurship education.
- [**Flutter Session Instructor**](https://github.com/GDGOC-SeoulTech/5th_Flutter_Session_5) · GDG on Campus in SeoulTech · `2025.11`

### Community & Leadership

- **App Core & Operations** · GDG on Campus in SeoulTech · `2025.09–2026.06`
- **President** · ITM Coding Education Volunteer Club · `2024.03–2024.12`

## Selected technologies

**Frontend & mobile**

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=111827" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" />
</p>

**Backend & data**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
</p>

**Delivery & quality**

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright" />
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest" />
</p>

## How I work

- Take ownership of product problems beyond the initially assigned implementation boundary.
- Follow a feature from the user-facing flow to its API contract, data model, operator workflow, and release path.
- Match verification to risk with focused tests, type checks, builds, reviewable diffs, and post-deployment checks.
- Treat concurrency, permissions, privacy, observability, and recovery as product requirements.

## AI-assisted development

My AI product work includes **PersonaWalk v2**, a local-first usability automation prototype built with Rust, Tauri, React, and Chromium CDP. I implemented its observation → decision → action → safety → artifact → report pipeline.

I use AI to accelerate repository exploration, implementation drafts, and review. I remain responsible for validating the source of truth, the resulting diff, and the real user outcome.

`inspect` → `isolate` → `implement` → `test / type-check / build` → `review` → `verify`

<a href="https://tokscale.ai/u/yeongJD"><img alt="Tokscale Stats for @yeongJD" src="https://tokscale.ai/api/embed/yeongJD/svg?template=graph&color=green&rank=percent&tokens=compact&cost=compact" /></a>
