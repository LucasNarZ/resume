# Resume Customization Guidelines

## Goal

Create the most relevant resume for each job, not the most complete one. The resume should make the recruiter quickly think: this candidate fits this role.

Prioritize:

- Job keywords and ATS terms.
- Recruiter expectations.
- Perceived level: intern, junior, or mid-level.
- Stack, responsibilities, product context, and company context.
- Real evidence from existing resumes in this repository.

## Mandatory Rules

- The resume language must match the job description language. Use English for English job descriptions and Portuguese for Portuguese job descriptions.
- Never add technologies, frameworks, tools, responsibilities, experiences, certifications, or skills that are not mentioned in at least one existing resume in this directory.
- If a job mentions a technology that does not appear in any existing resume, omit it or treat it only as job context. Never present it as candidate knowledge or experience.
- Do not infer skills by proximity. Example: Python/FastAPI does not imply Django; React does not imply Next.js unless Next.js already appears in an existing resume.
- Generated HTML resumes must follow the formatting, visual structure, and style of `TEMPLATE.html`, unless explicitly instructed otherwise.
- Every resume must include exactly one `Skills: ...` line below the header and before the experience section, listing all technologies mentioned anywhere in the resume, separated by commas.
- The resume must fit on a single page. If content overflows, cut by relevance 
  (least job-relevant bullets/certifications first), never by reducing font size 
  below readable thresholds or compressing margins excessively.
- Before finishing, review the resume for unsupported technologies or claims. Remove anything without a source in an existing resume.

## Relevance Rules

- Relevance beats completeness. Remove anything that does not increase fit for the specific job.
- Alignment beats technical impressiveness. Prefer the exact stack, responsibilities, and wording from the job description.
- The top of the resume must answer in about 10 seconds: role fit, main technologies, relevant experience, level, and work context.
- Preserve strong quantified impact when it is already supported by existing resumes. Do not remove standout metrics such as percentages, endpoint counts, test counts, cost reductions, or reliability improvements just to save space; cut weaker, less relevant content first.
- Avoid noise: unrelated technologies, too many skills, senior-sounding language for junior roles, unnecessary DevOps/cloud emphasis, unrelated frontend/backend details, extra projects, and weak certifications.

## Title

Use the target role plus the main relevant technologies when the job is specific.

Examples:

```text
Junior Backend Developer | Python, FastAPI, PostgreSQL
Junior Backend Developer | Node.js, TypeScript, NestJS
Junior Full Stack Developer | React, Node.js, REST APIs
```

If a user explicitly asks for the main job title without stack, extract only the role title from the job description.

## Skills Line

Use a single compact line:

```text
Skills: Python, FastAPI, REST APIs, PostgreSQL, Docker
```

Rules:

- Include every technology mentioned anywhere in the resume.
- Use comma-separated skills only.
- Do not group by categories.
- Do not list soft skills, responsibilities, or generic practices.
- Do not include technologies just because they exist in the candidate inventory; if a technology is not useful enough to be in `Skills: ...`, remove it from the resume too.

## Experience

Each bullet should follow:

```text
action + technology/context + result or impact
```

Keep bullets that prove fit with the job. Remove or reduce bullets that are technically good but not relevant.
Limit to 4-6 bullets per role for junior/mid-level resumes. If more than 6 are 
relevant, keep only the strongest matches to the job.
Always write experience bullets in first person consistently, such as "Desenvolvi", "Implementei", "Otimizei", "Automatizei", "Analisei" and "Participei". Do not mix third-person bullets in the same resume.
When shortening bullets, preserve the most recruiter-visible metric and the result. Prefer removing secondary context over removing quantified impact.

For junior roles, emphasize execution, APIs, integrations, tests, debugging, databases, learning ability, collaboration, and clear delivery. Avoid language that sounds too senior.

For mid-level roles, emphasize autonomy, ownership, architecture, reliability, performance, and measurable impact.

## Projects

Always include Sunlog.dev or PocScript unless the job clearly demands otherwise. Never select a project based on a single keyword match - always require an explicit, clear signal from the job description.
Project descriptions must stay concrete and evidence-based. Avoid generic phrases such as "complete application," "pieces," or "functional platform" unless followed by specific technologies, features, or numbers.
When a selected project has strong existing metrics or concrete proof points, include them if space allows. For Sunlog.dev, prefer concrete evidence such as REST APIs, relational modeling, authentication, API integration, production monitoring, 33 endpoints, and 100 unit tests over vague platform descriptions.

### When to use Sunlog.dev (default primary project)

Use as the main project for:

- Full stack roles (frontend + backend together)
- Node.js, TypeScript, or NestJS jobs
- Jobs mentioning React, Next.js, or modern frontend frameworks
- Jobs mentioning CI/CD, Docker, observability, or production deployment
- Generic/unspecified stack jobs with no clear domain or language signal

### When to use PocScript (default secondary project)

Add as a second project when the job mentions or values:

- Computer science fundamentals, algorithms, data structures
- Systems programming, low-level development, compilers, interpreters
- Tooling, infrastructure, or engineering-heavy work
- Technical curiosity, learning ability, or strong CS background
- Startups or engineering-focused teams without a rigid CRUD-only scope

Omit for clearly traditional, CRUD-only, business-process-focused roles with no engineering depth signal.

### When to use PCBuilderBR

Use instead of Sunlog.dev only when the job explicitly mentions:

- Python or FastAPI as the primary required stack
- E-commerce, marketplace, pricing, or product-catalog domains
- Compatibility rules, business calculations, or domain-specific validation logic as a core responsibility
- Web scraping or third-party data/price integration as a core focus, not just a generic "integrate third-party programs" phrase

Do not use PCBuilderBR based on generic phrases like "specifications," "improvements," "integrate software components," or "troubleshooting." These are too common across job posts to count as a signal.

### Default fallback

If the job has no specific stack, domain, or technical focus mentioned (truly generic junior/full stack postings), default to Sunlog.dev as the main project and PocScript as the second project. This pair shows the broadest and strongest engineering signal without relying on a stack-specific match.

### Selection checklist

Before finalizing project choice, confirm:

- Is the signal for this project explicit in the job description, not inferred from a single generic word?
- Would a recruiter reading the job post agree this project is the obvious fit?
- If no strong signal exists for any specific project, did I fall back to Sunlog.dev + PocScript?

## Education, Languages, Certifications

- Keep education objective.
- Preserve strong academic merit signals, especially full scholarships such as "Full scholarship (100%)," when they are part of the candidate inventory or explicitly provided by the user. Do not cut them unless space is impossible after removing weaker content first.
- If the candidate has a full scholarship at PUCPR, include it as "Bolsa integral (100%)" / "Full scholarship (100%)" in the education section whenever the resume language matches, unless the user explicitly asks to remove it.
- Keep languages aligned with the job language and requirements.
- Include certifications only when they directly reinforce the job.
- Database certification can stay for SQL, relational database, modeling, query performance, transaction, or data-heavy roles.
- Remove certifications when they add little fit or consume space.

## Customization Workflow

1. Read the job description and extract role, level, stack, responsibilities, work model, location, repeated terms, and company priorities.
2. Classify content as essential, useful, or noise.
3. Adjust the title and `Skills: ...` line.
4. Select only relevant experience bullets.
5. Choose the most aligned project.
6. Decide whether certifications help.
7. Remove noise.
8. Verify the resume is truthful, sourced from existing resumes, aligned with the job, and clear for HR.

## Positioning Defaults

### Backend

Emphasize REST APIs, databases, integrations, tests, workers, and business rules. Reduce frontend, advanced infrastructure, and unrelated certifications.

### Full Stack

Emphasize API + UI delivery, complete projects, React/Next.js when requested, backend, and database work. Reduce advanced cloud or observability unless requested.

### Cloud / Serverless / DevOps

Emphasize AWS Lambda, SQS, S3, DynamoDB, Terraform, GitHub Actions, Docker, Linux, CloudWatch, and CI/CD. Reduce frontend and unrelated projects.

### Python Backend

Emphasize Python, FastAPI, pytest, SQL, Docker, REST APIs, and integrations. Reduce Node/NestJS and frontend unless requested.

### Node.js Backend

Emphasize Node.js, TypeScript, NestJS, PostgreSQL, REST APIs, Jest, and Docker. Reduce Python/FastAPI and advanced AWS unless requested.

## Final Check

Before finalizing, ask:

- Does this resume look made for this job?
- Does the top answer the job fit in 10 seconds?
- Does the language match the job description?
- Are the title and `Skills: ...` line aligned with the job?
- Are the experience bullets relevant and level-appropriate?
- Is the chosen project the strongest fit?
- Is there any unsupported technology or claim?
- Is there any noise that should be removed?

The right resume is not the one that shows everything. It is the one that shows only what matters for the job.
