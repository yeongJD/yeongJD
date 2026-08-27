# Dongyeong Jeong (정동영)

> **Product-minded Full-Stack Engineer** · Mobile & Web · Backend & Data · Reliability & Automation

I build user-facing products and the systems behind them. I take ownership beyond assigned screens: when a product issue crosses mobile, web, admin, backend, or release boundaries, I investigate it and carry the change through QA and verification.

## Background

- **Education** — [Information Technology Management (ITM)](https://itm.seoultech.ac.kr/en/about/intro), **SeoulTech** · Mar 2020–Feb 2027 (expected) · Dual-degree program with **Northumbria University**
- **Experience** — Contract/Freelance Developer · late 2025–first half of 2026 (approx. 8–9 months) · **3 client projects delivered**; Startup product-development internship · Jul–Aug 2026
- **Programs** — **SW Maestro, 16th cohort** (completed) · Apr–Dec 2025; [**Promising Student Startup Team 300+ (U300+) — Growth Track**](https://u300.kr/about/u300) · 2026–Present
- **Teaching**
  - Coding Education Assistant Instructor for middle and high school students, Samsung Dream Scholarship Foundation-linked program · May 2026–Present
  - AI Startup Education PBL Instructor, **AI School Up** at AND Center (Seoul Metropolitan Nowon Youth Career Experience Center) · Jun–Aug 2026
  - [Flutter Session Instructor](https://github.com/GDGOC-SeoulTech/5th_Flutter_Session_5), **GDG on Campus in SeoulTech** · Nov 2025
- **Community** — **GDG on Campus in SeoulTech** · App Core & Operations · Sep 2025–Jun 2026
- **Leadership** — President, ITM coding education volunteer club · Mar–Dec 2024

## Selected projects

> Some repositories are non-public. I only describe non-sensitive technical scope and link public work where available.

### CoTeacher · Multi-client education platform

`Flutter` · `Next.js` · `React` · `Django` · `PostgreSQL`

- **My contribution:** Worked across mobile, user web, admin, and backend contracts; focused on catalog performance, request correlation, privacy, and pre-release validation.
- **Evidence:** Reduced a catalog N+1 path from **202 to 2 queries** on a 100-course fixture and verified a Django upgrade with **8,210 tests**.

### SYM · Education operations platform

`Spring Boot` · `React` · `Expo` · `PostgreSQL` · `Redis` · `Jenkins` · `AWS`

- **My contribution:** Improved attendance and student-management consistency, kept domain writes and outbox registration in one transaction, and moved notification side effects to a retryable worker.
- **Review ownership:** Found preview/commit snapshot races, lock-order risks, and missing authorization in peer PRs; re-reviewed the fixes before approval.

### OU · Commerce & operations

`React` · `Next.js` · `Supabase` · `PostgreSQL` · `Vercel` · `Playwright`

- **My contribution:** Connected storefront and admin workflows around payments, shipping, content, and incident handling.
- **Reliability work:** Added guarded recovery for reserved stock, coupons, and points; separated sandbox incidents and added fail-closed environment checks for builds and migrations.

### PersonaWalk v2 · Local-first AI usability automation

`Rust` · `Tauri` · `React` · `TypeScript` · `Chromium CDP`

- **My contribution:** Structured the workspace and built the observation → decision → action → safety → artifact → report pipeline.
- **Verification:** Added repeatable persona/scenario fixtures, structured-output failure handling, navigation-interruption recovery, workspace tests, and run probes.

### [Filient](https://github.com/BlueGreenSWM/Filient_MVP_2) · macOS file automation

`Flutter` · `SQLite` · `BLoC` · `Clean Architecture` · `AWS S3`

- **My contribution:** Connected rule, history, and rollback UI to domain flows; fixed destination-contract and recovery-path issues in file operations.
- **Product work:** Added macOS menu integration, Korean/English localization, user guides, and website improvements.

## Technologies used across projects

**Frontend & mobile**

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=111827" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" alt="Expo" />
</p>

**Backend & data**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
</p>

**Cloud & delivery**

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white" alt="Firebase" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" />
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" alt="Jenkins" />
</p>

**Quality & automation**

<p>
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright" />
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest" />
  <img src="https://img.shields.io/badge/Testcontainers-3C3C3C?style=flat-square&logo=testcontainers&logoColor=white" alt="Testcontainers" />
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white" alt="Tauri" />
</p>

## How I work

- Take ownership of product problems beyond the initially assigned implementation boundary.
- Follow a feature from the user-facing flow to its API contract, data model, operator workflow, and release path.
- Match verification to risk with focused tests, type checks, builds, reviewable diffs, and post-deployment checks.
- Treat concurrency, permissions, privacy, observability, and recovery as product requirements.

## AI-assisted development

I use AI to accelerate repository exploration, implementation drafts, and review. I remain responsible for validating the source of truth, the resulting diff, and the real user outcome.

`inspect` → `isolate` → `implement` → `test / type-check / build` → `review` → `verify`

<a href="https://tokscale.ai/u/yeongJD"><img alt="Tokscale Stats for @yeongJD" src="https://tokscale.ai/api/embed/yeongJD/svg?template=graph&color=green&rank=percent&tokens=compact&cost=compact" /></a>
