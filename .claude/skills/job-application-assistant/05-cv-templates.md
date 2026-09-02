---
framework_version: 1.4.3
---

# CV Templates and Tailoring Guide

## Template: LaTeX moderncv (Banking Style)

All CVs use the moderncv LaTeX package with the "banking" style and "blue" color scheme.

**Output file:** `cv/main_<company>_<role>.tex`
**Compile with:** **lualatex** on MiKTeX/TeX Live. pdflatex often fails on modern MiKTeX installs with `fontawesome5` font-expansion errors; lualatex handles the same sources cleanly.
**Master reference:** `cv/main_example.tex` (comprehensive CV with all competencies, experience, and achievements - use as source when building targeted CVs)

### Compile command

```bash
cd cv && lualatex -interaction=nonstopmode main_<company>_<role>.tex
```

Expected output: `Output written on main_<company>_<role>.pdf (2 pages, ...)`. Any page count other than 2 is a failure that must be fixed before presenting to the user.

## Section-by-Section Tailoring

### Profile Statement / Elevator Pitch (Best Practice)
This is the most important section to customize. It appears right after `\makecvtitle`.

Write 5-7 lines that function as an "elevator pitch": a concise, compelling introduction explaining why you're qualified for *this specific role*. Focus on what the employer gains from hiring you.

**For Software Development Engineer (SDE) roles:**
> Full-stack Software Engineer with 14+ months of hands-on experience building end-to-end applications across web, mobile, and backend stacks. Proficient in JavaScript/TypeScript, Python, Java, and Go, with production experience in scalable backend APIs (Node.js, Express), interactive UI components (React, Next.js, React Native), and SQL/NoSQL databases (PostgreSQL, MongoDB, Redis). Built and shipped production systems serving 500+ concurrent users with sub-200ms response times and 99.5%+ uptime. Strong problem-solver with a track record of end-to-end feature ownership, client collaboration, and thriving in fast-paced, high-impact environments.

**For Backend Software Engineer roles:**
> Backend-oriented Software Engineer with 14+ months of experience designing and shipping distributed systems, scalable REST APIs, and data-intensive backend services using Python, Node.js, TypeScript, and PostgreSQL. Hands-on experience building NLP preprocessing pipelines and LLM-integrated platforms at production scale. Proficient in serverless architectures, database optimization, event-driven caching, and real-time data processing. Strong problem-solver with a genuine interest in AI-native systems, open-source tooling, and building resilient backend infrastructure that handles messy, real-world data.

**For Full-Stack Developer roles:**
> Full-stack Software Engineer with 14+ months of experience building end-to-end applications from whiteboard design through production deployment. Proficient in JavaScript/TypeScript, Python, and Java, with production experience in scalable backend APIs (Node.js, Express), interactive UI components (React, Next.js), and SQL/NoSQL databases (PostgreSQL, MongoDB). Built production systems serving 500+ concurrent users with sub-200ms response times. Collaborates effectively with cross-functional teams in Agile environments, taking ownership of features from architecture through deployment.

### Core Competencies / Skills Section (Best Practice)
Reorder and emphasize based on the role. Use bold category labels.

List **5-7 key competencies** in bullet format, tailored to the specific job. For each competency, briefly explain how it adds value to the position.

**For SDE roles:**
- **Frontend & Mobile:** React.js, Next.js, React Native, Tailwind CSS, shadcn/ui, Redux
- **Backend & APIs:** Node.js, Express.js, REST APIs, GraphQL, JWT/OAuth/RBAC Authentication
- **Databases:** PostgreSQL, MongoDB, Redis, Prisma ORM, Query Optimization (EXPLAIN, Indexing)
- **Cloud & DevOps:** AWS (EC2, RDS, S3, Lambda), GCP, Docker, CI/CD (GitHub Actions), Vercel
- **Testing & Quality:** Jest, Mocha, Unit & Integration Testing, TDD, 85-95% Code Coverage

**For Backend roles:**
- **Backend & APIs:** Node.js, Express.js, REST APIs, Microservices, JWT/OAuth, Event-Driven Architecture
- **Databases:** PostgreSQL, MongoDB, Redis, Prisma ORM, Query Optimization (EXPLAIN, Indexing, Connection Pooling)
- **Cloud & Serverless:** AWS (EC2, S3, Lambda, RDS), Docker, CI/CD (GitHub Actions), Vercel, Railway
- **AI/ML & Data:** NLP Pipelines, LLM Integration, ETL Workflows, Data Validation, Applied Statistics
- **Architecture:** Distributed Systems, Serverless Computing, Event-Driven Design, Caching Strategies

### Education
- Always include your highest degrees
- For final year students, state "Expected completion [Month Year]"
- Include relevant coursework when relevant to the target role

### Professional Experience
- Rewrite bullet points to emphasize aspects most relevant to the target role
- Use 4-6 bullets for most recent role, 3-4 for previous, 2-3 for older
- **Emphasize measurable results** where possible: "Reduced processing time by X%", "Model adopted by the team"

### Publications
None listed

### Honors and Awards
None listed

### References
- Available upon request.
