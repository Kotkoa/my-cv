---
layout: default
---

## Andrey Kotko

**Fullstack Engineer**

**[kotkoa@gmail.com](mailto:kotkoa@gmail.com)** | residence: Spain + work-permit | +34-647-185-406  
[Linkedin](https://www.linkedin.com/in/kotkoa) | [Github](https://github.com/Kotkoa) | [Twitter](https://twitter.com/Kotkoa)  
[Telegram: @Kotkoa](https://t.me/Kotkoa) | [Download CV](assets/Andriy_Kotko_CV.pdf) | [Online CV](https://kotkoa.github.io/my-cv/)

### ABOUT ME

I build the frontend for AI-powered products — and I've shipped the hard parts most React engineers never touch: real-time AI streaming, conversational voice UIs, and deep GraphQL data layers. Senior Frontend Engineer, 6+ years of commercial React/TypeScript/Next.js across distributed international teams, most recently on contract. Currently building and running my own product (EV Libre) end-to-end while open to my next role.

**Proof:** at CloneForce (AI digital-clone platform on OpenAI, Pinecone/RAG, ElevenLabs) I built the core web app — real-time human–AI interaction via GraphQL subscriptions and streaming, a custom ElevenLabs voice chat UI, OAuth flows for Microsoft/Google/HubSpot, and a 50+ component MUI library. And I ship solo: [EV Libre](https://evlibre.cc) is my real-time PWA (React 19, Supabase Realtime, web push) live in production today. Earlier, at an equity-trading platform (HCX) I cut operational cost 30% by removing three blockchain libraries and migrating to bank payments.

**Differentiators:** deep Apollo Client expertise (custom cache strategies, type policies, AC3→4 migration, WebSocket subscriptions), design systems across four production projects (Yara International, HCX, Bridge The Gap, CloneForce), and a strong testing culture (Jest, Cypress, Playwright) with WCAG-accessible, performance-tuned UIs.

Based in Pego, Spain — work permit in hand, available now for remote roles across Europe (CET/CEST).

---

### TECHNICAL SKILLS

**Core (what I'm hired for):**
- **Frontend:** React, TypeScript, Next.js (SSR/SSG), JavaScript ES6+
- **Data:** Apollo Client / GraphQL, GraphQL Subscriptions, REST APIs
- **AI integrations:** ElevenLabs SDK, OpenAI API, RAG-aware UIs, OAuth (Microsoft, Google, HubSpot)
- **Design systems:** MUI, Tailwind, Storybook, Radix UI, Design Tokens, Accessibility (WCAG)
- **Testing:** Jest, Cypress, Playwright, React Testing Library

**Also experienced with:** Redux / Redux Toolkit, Jotai, MobX, React Context · SASS, Styled Components · Webpack, Vite, CI/CD, ESLint, Prettier · i18n, Nx Monorepo, Figma, Agile/Scrum

---

### EXPERIENCE

#### **Founder & Fullstack Engineer**

**EV Libre — [evlibre.cc](https://evlibre.cc) (Remote, Spain)**  
_October 2025 – Present_

Built end-to-end, solo: a real-time PWA that tracks EV charge-point availability on Spain's Iberdrola network and push-notifies users the moment an occupied port frees up. Live in production; moving from MVP to a paid subscription model. AI-assisted, hypothesis-first workflow with automated review gates and a full test battery on every change.

- Built a React 19 + TypeScript + MUI PWA on Vite: live port status, occupancy timers, nearby search, favorites, magic-link auth — strict TS, no `any`.
- Real-time UI via Supabase Realtime (WebSockets) with a polling fallback; service-worker web push via VAPID across Safari/PWA and Chrome.
- Designed a single-source data contract — a dependency-free Node 20 scraper (GitHub Actions cron) ships raw provider responses; one shared Supabase Edge Function (Deno) validates and writes snapshots to Postgres. Golden-fixture regression tests killed a whole class of parsing-drift bugs.
- Root-caused silent Chrome push failures (missing notification tag); hardened Postgres with explicit privilege revokes, validated via Supabase advisors.

**Tech Stack:** React 19, TypeScript, Vite, MUI, PWA, Supabase (Postgres, Edge Functions/Deno, Realtime), Node.js 20, GitHub Actions, Web Push/VAPID, Yarn workspaces, Vercel

---

#### **FullStack Engineer - Contractor**

**CloneForce, Newport Beach, California, United States (Remote)**  
_November 2024 – March 2026_

FullStack Engineer on an AI-powered digital clone platform that creates personalized AI assistants and coaches powered by OpenAI, Pinecone (RAG), and ElevenLabs, deployed across Slack, MS Teams, and web channels. Developed frontend interfaces for real-time human-AI interactions, conversational voice experiences, and automation workflows within the core web application.

- Developed real-time AI interaction interfaces using GraphQL subscriptions and streaming updates, enabling conversational clone experiences with live AI responses.
- Built and maintained a reusable UI component library with 50+ MUI-based components, improving visual consistency across the platform.
- Integrated ElevenLabs voice chat through the React SDK, replacing the default embed widget with a custom implementation for greater control over the conversational voice UI.
- Implemented real-time updates using GraphQL subscriptions (graphql-ws), enabling live clone interactions and streaming AI responses.
- Built OAuth integration flows for Microsoft, Google, and HubSpot, allowing clone skills to securely connect with external platforms on behalf of users.
- Improved frontend development workflows with strict TypeScript, ESLint, GitHub branch protections, and standardized architecture patterns to maintain consistent code quality.
- Improved page load performance by 1.2s through code splitting, lazy loading, and Apollo Client cache optimization.
- Implemented comprehensive Cypress E2E testing covering critical user flows across the AI assistant interface.

**Tech Stack:** React, Next.js (SSR), TypeScript, Jotai, Tailwind, SASS, MUI, Apollo GraphQL, GraphQL Subscriptions, ElevenLabs React SDK, Webpack, Jest, Cypress, Git

---

#### **FullStack Engineer — On the Beach (contract via Netguru)**

**On the Beach, Manchester, UK (Remote) — engaged through Netguru | B Corp™**  
_April 2025 – October 2025_

FullStack Engineer in a UK-based team modernizing the On the Beach holiday platform [onthebeach.co.uk](https://www.onthebeach.co.uk/), engaged as a contractor through Netguru ([netguru.com](https://www.netguru.com/)). Worked on a large legacy codebase: refactoring, component modernization, and improving maintainability, performance, and developer experience.

I collaborated with UK colleagues to deliver new features and experiments using JavaScript, TypeScript, GraphQL, React 19, and Next.js 15, employing feature flags for controlled rollouts and quick reversions. My work spanned frontend optimization, API integrations, and user experience enhancements, contributing flexibly across multiple areas of the platform.

As part of the Shop XP team, I've led and contributed to several key initiatives, including:

- Upgrading the Booking Flow technology stack to the latest React 19 and Next.js 15, improving performance, security, and engineering efficiency.
- Migrating from Apollo Client 3 to Apollo Client 4, enhancing data management, caching performance, and overall stability.
- Implemented feature flags for controlled rollouts and A/B experimentation, enabling data-driven UI decisions across 3 concurrent experiments.
- Implementing new UI toggle features, refining default search logic, and expanding tracking coverage for analytics and experimentation.

These improvements have resulted in faster page loads, smoother navigation between search and deal detail pages, and a more reliable, scalable foundation for future development.

**Tech Stack:** JavaScript ES6+, TypeScript, React 19, Next.js 15 (SSR/SSG), MobX, Apollo Client 4, GraphQL, Webpack, Git

---

#### **Frontend Engineer - Contractor**

**Human Capital Exchange (HCX), Los Angeles (Remote)**  
_September 2022 – January 2025_

Developed an [HCX](https://www.hcx.org/) trading platform for a new equity-based asset class using React, TypeScript, GraphQL, Jotai, and Jest.

- Configured a CI/CD pipeline with Jest unit tests and Cypress E2E integration, achieving 80%+ test coverage for critical user flows and cutting manual QA effort through automated user-flow validation.
- Streamlined account setup flows for multiple user types by integrating JSON Forms, Yup validation, and Apollo GraphQL, significantly improving onboarding and form completion.
- Collaborated with the backend team to extend and improve API integrations, adding new features and resolving issues that accelerated feature delivery.
- Simplified the payment architecture by removing three blockchain libraries, migrating to bank transactions, and implementing debit/credit card and bank account functionality, reducing operational costs by 30%.
- Integrated DocuSign for in-app application signing, streamlining document workflows and supporting KYC and legal compliance requirements.
- Contributed to onboarding documentation and developer integration processes, helping reduce onboarding time from one month to one week.
- Enhanced the global Material-UI theme system by consolidating shared styles and reusable patterns, reducing component development time across the platform.

**Tech Stack:** React, TypeScript, Jotai, Material-UI, GraphQL, Next.js, Jest, Cypress

---

#### **UI Engineer**

**Yara International, Singapore (Remote)**  
_August 2023 – January 2024_

Hired to enhance the usability and accessibility of [Yara International](https://www.yara.com)'s design system, focusing on creating new components and refactoring existing ones, utilizing designs by our team of designers on Figma. This role required technical proficiency and design skills to develop components within the company's React-based design system. The project was managed in a Git repository with NxMonorepo, consolidating web (React) and mobile (React Native) libraries for developers.

- Enriched a React library with 10+ new components and refactored existing ones, improving accessibility to meet global WCAG standards.
- Conducted an accessibility audit and initiated improvements, ensuring the components meet global accessibility standards.
- Updated design system documentation to Storybook@7, optimizing infrastructure, and overhauling documentation for improved clarity and utility.
- Developed a new token structure to streamline design-to-code workflows, facilitating easier adoption of design principles and more consistent implementation across projects.
- Team Collaboration: Worked closely with designers to refine and implement component designs, discussing the overall look of the Storybook theme.
- Quality Assurance: Implemented rigorous code review and testing protocols to ensure component reliability across various browsers and devices, addressing bugs promptly to maintain system integrity.

**Tech Stack:** React, TypeScript, Storybook, Radix UI, Figma, Design Systems, Design Tokens, Accessibility (WCAG), GitHub, React Native

---

#### **Frontend Engineer**

**Bridge The Gap, Europe (Remote)**  
_December 2022 – September 2023_

I was recruited as a Frontend and UI developer to join [Bridge the Gap](https://bridge-the-gap.dev), a European-based team of developers led by Varia Stepanova, to enhance the team's capabilities. This role enabled me to combine my technical expertise with a keen sense of design, contributing significantly to our digital systems.

- Maintained a Next.js website, migrating the platform from Next.js 12 to 14.
- Updated the design system npm library with new reusable React components.
- Migrated the web application from Gatsby 3 to Gatsby 5, improving compatibility, maintainability, and build performance.
- Refactored project components to improve performance and maintainability, including upgrading dependencies such as @mdx-js/react, improving code quality with ESLint and Prettier, and enhancing UI components and image rendering across web pages.
- Contributed to the design system npm library by implementing major updates to the ProfileCard component across multiple releases, improving layout styling, UI consistency, and component functionality.

**Tech Stack:** React.js, Next.js, GatsbyJS, Jest, Tailwind CSS, Figma, Design Systems

---

#### **Frontend Developer**

**Root Name System (RNS), Singapore (Remote)**  
_November 2021 – July 2022_

Hired in international tech team as a frontend developer to enhance and manage their innovative digital identity platform, [rns.id](https://rns.id/) (Root Name System). The project aimed to develop an application by issuance of digital IDs of digital residence islands of Palau. My role was on optimizing and redesigning web applications, integrating new features of Document verifications, and elevating quality through measures such as Sentry.io logging, TypeScript migration, and Jest test coverage. A key part of my responsibilities included fast-forward landing page creation to meet marketing team goals.

- Developed 3 landing pages, 2 web apps, and 35 HTML email templates for user subscriptions, improving user engagement and implementing features such as ID verification, TypeScript migration, and Jest test coverage.
- Refined MaterialUI components into Styled Components, improving UI flexibility, responsiveness, and load time.
- Managed complex application state using Redux and Redux Toolkit; later migrated to MobX, reducing boilerplate and improving maintainability across the application.
- Implemented a multi-site (multizone) experience (SSR and SPA) as one web app, developing both websites independently with the same level of control.
- Integrated internationalization using i18n, enabling localization for 12 new languages and expanding global reach.

**Tech Stack:** React.js, Next.js (SSR), TypeScript, JavaScript ES6+, Tailwind, SASS, Redux, Redux Toolkit, MobX, Material-UI, Styled Components, i18n, Jest, Webpack, S3, Git

---

#### **Freelance Javascript Developer (React.JS & Node.JS)**

**Freelance, Tenerife, Spain (Remote)**  
_January 2020 – December 2021_

I was acting as a full-stack engineer, creating services and endpoints with Express and frontend logic with React. I was responsible for the development of a web application for a local business. The application was built with React, Redux, and Node.js, and was designed to be responsive and accessible across various devices.

- Integrated Javascript Playground for creating sandboxes with the ability to run and check code snippets without any need for deployment
- Migrated to clean React with Context API
- Frontend with React/Redux
- RESTful API's Node.js and Express
- Implemented low-level CSS framework Tailwind

**Earlier (2004–2020):** Web/CMS development (WordPress, HTML/CSS, SEO automation with JavaScript across 20+ stores), project & account management (Ramotion — iOS/AppStore), and 3D design/rendering. Foundation in product, client communication, and small-team leadership before moving full-time into frontend engineering.

---

### EDUCATION

#### **Bachelor's Degree in Instrument Engineering**

**Sevastopol State Technical University, Ukraine**  
_1999 – 2004_

---

### LICENSES & CERTIFICATIONS

- **Claude Code: Professional AI Setup** – Frontend Masters (2025)

---

### LANGUAGES

- **English:** Fluent (B2+)
- **Ukrainian:** Native
- **Russian:** Native
- **Spanish:** Conversational

---

### PORTFOLIO

- **[EV Libre](https://evlibre.cc)** – Real-time PWA tracking EV charger availability (Spain/Iberdrola), with web push when a port frees up. React 19 · TypeScript · Vite · MUI · Supabase (Realtime, Edge Functions, Postgres). **Live in production, built solo.**
- **[Bitcoin Testnet Wallet](https://github.com/kotkoa/bitcoin-wallet/)** – Minimalist Bitcoin wallet using React.js, Next.js, and Redux Toolkit.
- **[Rick and Morty Explorer](https://rickandmorty-2024.vercel.app/)** – Character browser using **GraphQL API**, React, and TypeScript.
- **[Simple Auth App](https://github.com/Kotkoa/simple-auth-app)** – OAuth integration (Google & Microsoft) — mirrors production auth flows.
