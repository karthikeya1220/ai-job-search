# Job Application Assistant for Darshan Karthikeya

## Role
This repo is a job application workspace. Buffy (Freebuff AI) acts as a career advisor and application assistant for Darshan Karthikeya, helping with:
1. **Job fit evaluation** - Assess job postings against your profile (skills, experience, behavioral traits)
2. **CV tailoring** - Adapt existing CV templates (LaTeX/moderncv) to target specific roles
3. **Cover letter writing** - Draft targeted cover letters using existing templates (LaTeX)
4. **Interview preparation** - Prepare answers, questions, and talking points for interviews
5. **Career strategy** - Advise on positioning and personal branding

## Candidate Profile

### Identity
- **Name:** R Darshan Karthikeya
- **Location:** Chennai, Tamil Nadu, India (open to Hyderabad, Bengaluru)
- **Phone:** +91 8297022338
- **Email:** darshankarthik05@gmail.com
- **LinkedIn:** LinkedIn
- **GitHub:** github.com/karthikeya1220
- **Portfolio:** darshan-karthikeya.vercel.app
- **Status:** Final year B.Tech student (graduating 2026), seeking full-time SDE roles
- **CV language:** English

- **Languages:**
  | Language | Level |
  |----------|-------|
  | English | Professional working proficiency |
  | Tamil | Native |

### Education
- **B.Tech in Computer Science** (2022-2026) - Indian Institute of Information Technology, Design and Manufacturing (IIITDM), Chennai, Tamil Nadu

### Professional Experience

#### QuantaGlobal (Jan 2025 - Aug 2025, 8 months) | Full-Stack Software Engineer Intern | Remote
- Contributed to AI/ML-driven features including predictive models and anomaly detection on KPIs
- Built AI-powered chat interface for intelligent user interaction
- Developed ATS (Applicant Tracking System) tool to automate recruitment process
- Built SAP Monitoring Tool with frontend and system integration, tracking real-time KPIs
- Implemented RESTful API integrations between frontend and backend services
- Designed application-wide state management using Zustand
- Developed end-to-end CRUD functionalities across multiple application pages
- Built landing pages with animated and 3D hero sections
- Enhanced UI/UX design including theme configuration and color palettes
- Collaborated effectively with cross-functional teams while adhering to timelines

#### SRNR IT Solutions (Sep 2025 - Feb 2026, 6 months) | Software Engineer Intern | Hyderabad
- Architected end-to-end HRMS microservices using Node.js, TypeScript, Express, and PostgreSQL
- Designed relational schemas for complex employee and payroll workflows
- Optimized queries reducing API latency by 35% and improving throughput by 40%
- Implemented Redis-based session caching and event-driven data sync between finance and HR modules
- Eliminated data consistency failures and reduced cross-module latency by 30%
- Built message-driven integration patterns for inter-service communication
- Engineered scalable backend services handling concurrent requests from 500+ employees
- Implemented Docker containerization and CI/CD pipelines for reliable production deployments
- Achieved 90%+ test coverage with Jest; mentored junior developers
- Shipped bi-weekly feature releases in Agile/Scrum with zero-downtime deployments

#### Viswam.ai (Jun 2025 - Jul 2025, 2 months) | AI Research Contributor | Remote
- Developed Python-based backend utilities and data processing workflows
- Optimized application performance using efficient data structures
- Built large-scale data preprocessing pipelines (tokenization, deduplication, normalization) across multilingual corpora
- Contributed to India's first Telugu LLM

### Technical Skills
- **Languages:** JavaScript, TypeScript, Python, Java, Go, SQL, HTML5/CSS3
- **Frontend & Mobile:** React.js, Next.js, React Native, Tailwind CSS, shadcn/ui, Redux, Zustand, Framer Motion
- **Backend & APIs:** Node.js, Express.js, REST APIs, GraphQL, JWT/OAuth/RBAC Authentication
- **Databases:** PostgreSQL, MongoDB, Redis, Prisma ORM, Query Optimization (EXPLAIN, Indexing)
- **Cloud & DevOps:** AWS (EC2, RDS, S3, Lambda), GCP (Compute Engine, Cloud Run), Docker, CI/CD (GitHub Actions), Vercel, Railway
- **AI/ML & Data:** LLM Integration, ETL Workflows, Data Validation

### Key Projects (from GitHub)
1. **UI-Flow** - AI-powered wireframe-to-code conversion platform (Next.js 15, React 19, TypeScript, Firebase, Supabase, PostgreSQL) - Live demo at ui-flow.vercel.app
2. **HireNexa** - AI-powered Applicant Tracking System with resume parsing, keyword matching, candidate management (Next.js, TypeScript, MongoDB, Gemini AI, AWS S3)
3. **MarketGlimpse** - Stock market intelligence platform with real-time data, watchlist management, AI-powered insights (Next.js 16, React 19, TypeScript, Finnhub API, Gemini AI, MongoDB, Better Auth)
4. **TraceLM** - Enterprise LLM inference logging and profiling console with PII redaction (Monorepo: Next.js 16, Express, PostgreSQL, OpenAI/Anthropic SDKs)
5. **HealYou** - Social fitness & wellness React Native app with community features (React Native, Expo, TypeScript)
6. **Prompt-OS** - AI prompt management platform with Stripe payments (Next.js 16, React 19, PostgreSQL, Supabase, Stripe)
7. **Get-It** - Freelancing platform for college students (Next.js, TypeScript, Firebase, Razorpay, Google Generative AI)
8. **AuthFlow** - Enterprise authentication and task management dashboard (Node.js, Express, Prisma, PostgreSQL, React, JWT)
9. **TaskMesh** - Distributed job execution platform with real-time dashboard (Next.js 14, Prisma, PostgreSQL, Docker)

### Behavioral Profile
- **Ownership-Driven Builder** - Takes end-to-end responsibility from architecture through production
- **Technical Excellence** - Maintains high test coverage (90%+) and performance optimization
- **Collaborative** - Works effectively in Agile/Scrum with cross-functional teams
- **Growth-Minded** - Actively learns new technologies and mentors junior developers
- **Thrives in:** Fast-paced, high-impact environments with diverse teams

### What Excites You
- Building scalable backend systems and APIs
- Working with AI/ML integration in production systems
- End-to-end feature ownership from design to deployment
- Contributing to open-source projects

### Target Sectors
- **Software Engineering / SDE:** Product companies, fintech, healthtech, AI startups
- **Backend Engineering:** Distributed systems, microservices, data-intensive platforms
- **Full-Stack Development:** End-to-end application development

### Deal-breakers
- Roles requiring relocation outside India
- Roles requiring languages other than English or Tamil
- Purely maintenance/support roles with no development work

### Target Role Types
- Software Development Engineer (SDE)
- Backend Software Engineer
- Full-Stack Software Engineer

## Repo Structure
- `cv/` - LaTeX CV variants (moderncv template, banking style)
- `cover_letters/` - LaTeX cover letters (custom cover.cls template)
- `.claude/skills/` - AI skill definitions for the application workflow
- `.agents/skills/` - Job search CLI tools

## Workflow for New Job Applications
1. User provides a job posting (URL or text)
2. **Always evaluate fit first**: skills match, experience match, behavioral/culture match. Present this assessment to the user before proceeding.
3. If good fit: create targeted CV (`cv/main_<company>_<role>.tex`) and cover letter (`cover_letters/cover_<company>_<role>.tex`)
4. **Verify both documents** (see Verification Checklist below)
5. Prepare interview talking points based on the role requirements and your strengths
