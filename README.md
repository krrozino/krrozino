<div align="center">

# Hi, I'm Sergio Izaque

### Software Developer · Web & Mobile · Computer Science Education @ UFF

I turn real-world problems into **software that people can use**, from production web/mobile products to engineering tools, geospatial research and computer vision.

[![Portfolio](https://img.shields.io/badge/Portfolio-cerjo.dev-168CFF?style=for-the-badge&logo=vercel&logoColor=white)](https://cerjo.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sergio%20Izaque-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sergioizaque)
[![Instagram](https://img.shields.io/badge/Instagram-@cerjo.dev-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/cerjo.dev/)

</div>

---

## About me

I'm a **Computer Science Education student at Universidade Federal Fluminense (UFF)** and an **IT Technician**. I work across the software lifecycle: understanding a problem, designing the experience and data model, implementing features, testing, deploying and improving what ships.

My interests include full-stack engineering, product development, mobile apps, application security, observability, automation, geospatial software and computer vision.

**Portfolio and client work:** [cerjo.dev](https://cerjo.dev)

## Selected work

My projects span **real-world products, open-source education, academic research, developer tools, and client websites**. I distinguish deployed software, research prototypes, and features still under development.

### Flagship platforms

**O Livro Vermelho — RPG Platform** · Long-running project (1+ year) · Used by a private RPG group · Private repository

My largest and longest-running software project. A tabletop RPG platform with automated character sheets, campaign management, a game-master dashboard, tactical maps, initiative and synchronized combat, compendiums, homebrews, community features and administration. Its ongoing engineering work includes access control, mobile usability, cost-aware Firebase usage and isolated emulator-based release tests. There is no unrestricted public demo.

**Stack:** React · TypeScript · Vite · Zustand · Firebase (Auth, Firestore, RTDB, Storage, Functions) · PixiJS

**Gym Management Platform (AcademiaApp)** · Used in a real training environment · Private repository · [Case study](https://cerjo.dev/projetos/academia)

A web/mobile ecosystem for personal trainers and students. The trainer dashboard supports student management, exercise catalogs, workout prescriptions and periodization. The student app supports workout history, load tracking, rest timers, Powerlifting progression and offline-first usage. Separate staging/production environments and automated domain/Firestore Rules tests support controlled releases.

**Stack:** Next.js · React Native / Expo · TypeScript · Firebase / Firestore · Vitest · Vercel

**NutriApp — Continuous Nutrition Follow-up** · Active development and supervised demos · Private repository

A nutrition-professional workflow designed to reduce repetitive patient-by-patient follow-up through organized patient records, check-ins, journeys, attention queues and plan-specific tracking. A monorepo separates the professional dashboard, patient app, testable domain rules and AI integration contracts. **Real-patient production use remains gated** by security, quality and operational validation; planned automation is not represented as a launched service.

**Stack:** Next.js · TypeScript · Expo · Firebase · Vitest · Domain modules

**[WinLab Configurator](https://github.com/krrozino/winlab)** · MVP 0.9 pilot candidate · [Case study](https://cerjo.dev/projetos/winlab)

A local-first Windows configuration toolkit for shared PCs in schools and small organizations. Generates PowerShell packages covering account policies, AppLocker, browser/USB controls, inventory, maintenance and recovery. Includes preflight checks, SHA-256 integrity manifests, preview-before-apply workflows and rollback procedures. Automated validation exists; a physical pilot and Windows desktop companion are separate ongoing work.

**Stack:** Next.js · TypeScript · PowerShell · Windows policies · GitHub Actions

### Open-source education & applied research

**[Taekwondo para Todos — PT-BR Encyclopedia](https://github.com/krrozino/kukkiwon-ptbr-tkd)** · Public educational prerelease · [Website](https://kukkiwon-ptbr-tkd.kukkiwon-ptbr-tkd.workers.dev/)

A free, nonprofit, community-driven Taekwondo learning resource in Brazilian Portuguese. Features an interactive body atlas, catalog navigation, Poomsae introductions, fundamentals, study tools and curriculum organization. Draft technical content is **not** an approved or validated catalog; references require source verification and human review. **Independent project, not affiliated with or endorsed by Kukkiwon.**

**Stack:** Astro · React · TypeScript · Supabase / PostgreSQL · Cloudflare Workers · Vitest / Playwright

**[Pádua FloodSim](https://github.com/krrozino/padua-floodsim)** · Experimental academic release · [Web app](https://padua-floodsim.vercel.app) · [DOI](https://doi.org/10.5281/zenodo.22928810) · [Case study](https://cerjo.dev/projetos/padua-floodsim)

Geospatial software and research focused on the Rio Pomba in Santo Antônio de Pádua, Brazil. The public viewer displays **11 official SGB reference inundation extents from 3.00 m to 5.50 m**. Research is organized around monitoring observed conditions, investigating short-term forecasts, and translating validated results into spatial impact. **Not an operational forecast or official flood-warning system.**

**Stack:** Next.js · TypeScript · MapLibre GL · GeoJSON · Python / geospatial research

**Sports Motion Analyzer** · Experimental computer-vision research · Private repository

Python-based motion capture and offline sports analysis focused on the **Powerlifting squat**. Includes MediaPipe pose tracking, camera-view awareness, optional barbell tracking, recorded measurements, quality diagnostics, temporal phase analysis and a reusable biomechanics metrics core. A research tool, not a validated competition judging system.

**Stack:** Python · MediaPipe · OpenCV · Computer Vision

**[EduGrid](https://github.com/PaduaDevs/EduGrid)** · Collaborative academic project with PaduaDevs · Sprint 0

An open-source initiative for educational timetable optimization, conflict-aware scheduling and resource allocation. The team is establishing constraints, architecture and a proof of concept. Automated timetable generation remains a **planned capability**.

**Planned stack:** Next.js · NestJS · PostgreSQL · Python / OR-Tools

### Academic applications & products in development

**[StageTrack](https://github.com/krrozino/stagetrack)** · Active development · [Preview](https://stagetrack-ashy.vercel.app)

A supervised-internship management platform for student records, activity logs, hour tracking, advisor reviews and coordination workflows. Its engineering foundation uses Supabase Auth, secure server-side sessions, PostgreSQL migrations and Row Level Security. Functional flows are being expanded and validated; it is not presented as institution-wide deployed software.

**Stack:** Next.js · TypeScript · Supabase Auth · PostgreSQL · RLS · Zod

**[DevBoard](https://github.com/krrozino/devboard)** · Foundation / pre-MVP · [Preview](https://devboard-phi-six.vercel.app)

A developer observability concept designed to transform repository activity into explainable project-health signals and actionable attention items. The current foundation contains a Next.js application, PostgreSQL/Drizzle schema, domain modules, tests and CI. Full live GitHub synchronization is still a roadmap milestone.

**Stack:** Next.js · TypeScript · PostgreSQL · Drizzle ORM · Vitest

**EloDo — Martial Arts School Management** · Experimental foundation · Private repository

A multi-school platform being designed for martial arts academies, including schedules, attendance, memberships, graduations and organization-level permissions. The codebase contains a React/TypeScript UI foundation and a controlled **local authentication** experiment. Remote Supabase services, production RLS, real school data and commercial release remain future gates.

**Stack:** React · TypeScript · Vite · Tailwind CSS · Supabase / PostgreSQL (planned)

### Client work, portfolio & interactive experiences

**[cerjo.dev — Professional Portfolio](https://github.com/krrozino/cerjo-dev)** · [Live site](https://cerjo.dev)

My professional website and contact point. Includes responsive navigation, structured metadata, accessibility improvements, Vercel Analytics and dedicated case studies for selected projects, distinguishing real client work, prototypes and research.

**Stack:** HTML · CSS · JavaScript · Vercel

**[Mães que Oram — Landing Page](https://github.com/krrozino/landing-page-rosangela)** · Client website · [Live](https://landing-page-rosangela.vercel.app) · [Case study](https://cerjo.dev/projetos/maes-que-oram)

A responsive website for a real community/client initiative, combining its visual identity, social channels and links to digital products in a lightweight experience.

**[Make Me Angel — Editorial Landing Page](https://github.com/krrozino/landing-page-angelica)** · Client-oriented web design project

A responsive editorial landing page for a beauty-education offer, presenting **Protocolos de Atendimento 3X** through a clear information hierarchy and calls to action. Its public repository demonstrates the interface; it is not described as a launched course platform.

**[Injorn Web](https://github.com/krrozino/injorn-web)** · Interactive fictional-world website · [Preview](https://injorn-web-preview.vercel.app)

A player-facing RPG-world experience with contextual storytelling, responsive visual scenes and reusable hotspots, keeping game-master spoilers and private campaign planning out of the public application.

**[Vértice Performance](https://github.com/krrozino/vertice-performance)** · Conceptual UI case · [Live](https://vertice-performance-alpha.vercel.app/)

A **fictional** premium-gym landing page demonstrating responsive layouts, semantic structure and conversion-oriented interaction. Business details and testimonials are illustrative.

### Early-stage product explorations

**WorkEasy** · Product design / pre-MVP · Private repository — A mobile-first service-management concept for independent professionals, initially exploring cleaning/maintenance and carpentry workflows, tenant isolation and estimates. No live customer product.

**PDVSys — Kiosk Point of Sale** · Technical prototype v0.2 · Private repository — An offline-first Windows touchscreen POS concept with local sales records and thermal ticket workflows. Physical hardware, recovery and fiscal/operational validation are required before real use; the repository currently documents a prototype rather than a released POS.

---

## Technologies I work with

## Languages

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)

## Web & Frontend

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

## Mobile

![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)

## Backend, Data & Cloud

![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=for-the-badge&logo=drizzle&logoColor=000000)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

## Quality & Engineering

![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white)

## Geospatial & Computer Vision

![MapLibre](https://img.shields.io/badge/MapLibre_GL-396CB2?style=for-the-badge&logo=maplibre&logoColor=white)
![GeoJSON](https://img.shields.io/badge/GeoJSON-000000?style=for-the-badge&logo=geojson&logoColor=white)

## Computer Vision & AI

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white)
![AI](https://img.shields.io/badge/AI-Integrations-168CFF?style=for-the-badge&logo=openai&logoColor=white)

## Tools

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)


## How I approach engineering

I favor **maintainable and testable products** over demos that only look finished. That means version control, clear requirements, privacy-conscious architecture, distinct development/production environments, automated quality gates and honest project-status labels.

I also use AI-assisted development as part of my workflow, with code review, verification and source control still treated as engineering responsibilities.

---

<div align="center">

**Let's connect:** [Portfolio](https://cerjo.dev) · [LinkedIn](https://linkedin.com/in/sergioizaque) · [Instagram](https://www.instagram.com/cerjo.dev/)

*Building, learning and improving one project at a time.*

</div>
