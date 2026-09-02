---
framework_version: 1.2.6
---

# Job Evaluation Framework

## Eligibility Gate — run before scoring

The candidate is an Indian citizen seeking roles in India (Hyderabad, Bengaluru primarily). No work permit issues for domestic roles. For international roles, verify visa sponsorship availability.

## Language Gate — run before scoring

The candidate's working languages are English (professional) and Tamil (native). Most software engineering roles in India operate in English, so this gate typically passes. Flag roles requiring Hindi or other languages as potential friction.

## Scoring Dimensions

### 1. Technical Skills Match (0-100)
How well do the required/preferred skills align with the candidate's capabilities?

| Score | Meaning |
|-------|---------|
| 80-100 | Core requirements are primary skills |
| 60-79 | Most requirements match, 1-2 gaps that are learnable |
| 40-59 | Partial match, significant upskilling needed |
| 0-39 | Fundamental mismatch |

**Strong match areas:** JavaScript/TypeScript, Node.js, Express.js, React.js, Next.js, PostgreSQL, MongoDB, Redis, REST APIs, Docker, CI/CD, Zustand, event-driven architecture
**Moderate match areas:** Python, Go, GraphQL, AWS/GCP, React Native, Prisma ORM, LLM integration
**Weak match areas:** Systems programming, mobile-native development (Swift/Kotlin), legacy enterprise stacks, Kubernetes/container orchestration at scale

### 2. Experience Match (0-100)
Does work history align with what they're looking for? Match on the function and nature of the work performed, not the literal job title.

| Score | Meaning |
|-------|---------|
| 80-100 | Direct experience in the same domain and role type |
| 60-79 | Related experience, transferable skills clear |
| 40-59 | Adjacent experience, would need to make the case |
| 0-39 | Unrelated experience |

**Strong:** Full-stack web development, backend API design, database optimization, production deployments, microservices architecture, AI/ML integration
**Moderate:** Cloud infrastructure, system design at scale, DevOps/SRE practices
**Entry-level:** Mobile development, data engineering, site reliability engineering

### 3. Behavioral/Culture Fit (0-100)
Does the role and company culture match the behavioral profile?

| Score | Meaning |
|-------|---------|
| 80-100 | Culture strongly matches behavioral preferences |
| 60-79 | Mixed signals but mostly compatible |
| 40-59 | Some friction areas |
| 0-39 | Significant culture mismatch |

**Red flags to research:** Companies with high turnover, toxic work cultures, unclear ownership structures, or heavy bureaucracy that prevents rapid feature delivery.

### 4. Location & Logistics (Pass/Fail + Notes)
- Within Hyderabad/Bengaluru: PASS
- Remote with occasional office: PASS
- Requires relocation outside India: FAIL (deal-breaker)
- Requires Hindi or other non-English languages: FLAG (discuss with user)

### 5. Career Alignment & Motivation (0-100)
Does this role advance career goals and contain tasks that energize?

| Score | Meaning |
|-------|---------|
| 80-100 | Strongly aligned with career direction, clear growth path |
| 60-79 | Good role but only partially aligned with long-term goals |
| 40-59 | Decent job but doesn't build toward career goals |
| 0-39 | Dead end or backwards step |

**Career goals:**
- Build expertise in scalable backend systems and distributed architectures
- Gain deeper experience with LLM integration in production systems
- Grow into a senior engineering role with architectural responsibilities

**Motivation filter:** Evaluate not just whether you *can* do the tasks, but whether the tasks will *energize* you. Consider:
- Tasks that energize: Building new features, optimizing performance, architecting systems, working with modern tech stacks, AI/ML integration
- Tasks that drain: Pure maintenance work, bureaucracy-heavy environments, siloed teams
- Non-task factors: Team culture, technical leadership, learning opportunities

**Life situation alignment:** Consider personal constraints:
- **Security**: Final year student, seeking first full-time role
- **Flexibility**: Open to hybrid/remote within India
- **Professional development**: Looking for roles with mentorship and growth opportunities

## Output Format

Present the evaluation as:

```
## Job Fit Evaluation: [Role] at [Company]

| Dimension | Score | Notes |
|-----------|-------|-------|
| Technical Skills | XX/100 | [brief note] |
| Experience Match | XX/100 | [brief note] |
| Behavioral Fit | XX/100 | [brief note] |
| Location | PASS/FAIL | [brief note] |
| Career Alignment | XX/100 | [brief note] |

**Overall Score: XX/100** (weighted average of scored dimensions)

### Verdict: [Strong Fit / Good Fit / Moderate Fit / Weak Fit / Poor Fit]

### Key Strengths for This Role
- [bullet points]

### Gaps to Address
- [bullet points]

### Recommendation
[1-2 sentences: apply/skip/apply with caveats]

### Company Research Checklist
- [ ] Checked company website (mission, values, recent news)
- [ ] Checked review sites (Glassdoor, etc.)
- [ ] Checked LinkedIn for team size, recent hires, connections
- [ ] Checked media for restructuring, growth, or workplace issues
- [ ] Identified network contacts who may know the team/manager
```

## Weighting
- Technical Skills: 30%
- Experience Match: 25%
- Behavioral Fit: 15%
- Career Alignment: 30%

(Location is pass/fail, not weighted)

## Thresholds
- **Strong Fit** (75+): Definitely apply, tailor everything
- **Good Fit** (60-74): Apply, address gaps in cover letter
- **Moderate Fit** (45-59): Consider carefully, discuss with user
- **Weak Fit** (30-44): Probably skip unless strategic reasons
- **Poor Fit** (<30): Skip
