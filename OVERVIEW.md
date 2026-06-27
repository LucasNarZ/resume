## Professional Profile (Reusable Base)

Full Stack Developer with a strong focus on backend and cloud infrastructure, working in production environments with serverless architectures on AWS. Practical experience building APIs, automating infrastructure with Terraform, implementing CI/CD pipelines, and adopting asynchronous messaging for distributed systems.

Currently working at SmartLy, where I contributed directly to the evolution of the system architecture, including the introduction of infrastructure as code (IaC), deployment automation, and reliability and cost improvements. Experience with monitoring and observability using metrics and logs to identify failures, optimize performance, and support technical decisions.

In addition to backend work, I also develop full stack applications with React and Next.js, and have practical experience with Docker, daily Linux environments, and Bash scripts for process automation. Recently, I have been expanding my knowledge in virtualization and infrastructure to strengthen my foundation for DevOps/SRE positions.

I aim to work in environments that value solid software engineering, scalability, and autonomy, contributing both to software development and platform evolution.
---

## Personal Data (Always at the Top of the Resume)

Always include:

* **Name:** Lucas Narloch Zabla
* **Email:** [lucasnarloch123@gmail.com](mailto:lucasnarloch123@gmail.com)
* **Phone:** +55 (41) 98719-8655
* **Location:** Curitiba - PR, Brazil
* **GitHub:** [https://github.com/LucasNarZ](https://github.com/LucasNarZ)
* **LinkedIn:** [https://linkedin.com/in/lucasnarloch](https://linkedin.com/in/lucasnarloch)
* **Portfolio:** [https://lucasnarz.github.io/Portfolio](https://lucasnarz.github.io/Portfolio)

---

## Professional Experience (Structured Model)

**Role:** Backend Developer (or Backend with Cloud/DevOps focus)
**Company:** SmartLy Fabricacao de Dispositivos Inteligentes Ltda.
**Period:** 09/2024 - Current

**Responsibilities and deliveries:**

* Developed an endpoint for migrating data between IoT devices, integrating 4 services (MySQL, DynamoDB, S3, and AWS IoT Core) through MQTT.
* Implemented automated tests for FastAPI APIs with pytest, including 20 integration tests with Testcontainers and 50 unit tests, improving change safety and reducing regression risk.
* Developed a cron-scheduled worker for automatic sunset time updates, identifying affected routines, persisting changes in the database, and sending updates to devices through MQTT.
* Implemented asynchronous processing with SQS to decouple critical flows and improve request stability.
* Optimized AWS Lambda functions in Python, reducing average errors every 5 minutes from 113 to 5, a 95.6% reduction, increasing production system reliability.
* Led the consolidation of multiple AWS Lambda functions into endpoint-based FastAPI architecture, reducing operational complexity, improving code cohesion, and simplifying the deployment process.
* Structured infrastructure as code with Terraform from scratch, replacing manual AWS console management with versioned repository changes and the creation of a staging environment.
* Automated deployments with CI/CD pipelines in GitHub Actions, replacing manual processes and reducing configuration risks in production.
* Introduced asynchronous processing with SQS to decouple notification sending and publishing to AWS IoT Core, removing blocking operations from the main request flow.
* Reduced infrastructure costs by 20% through CloudWatch metric analysis, identifying and removing idle resources.
* Worked on log and metric analysis with CloudWatch, identifying bottlenecks, production failures, and operational improvement opportunities.
* Developed integrations between services (MySQL, DynamoDB, S3, and IoT Core), ensuring data consistency across backend and cloud components.
* Created Docker utilities to simulate local environments and support integration testing.
* Automated CI/CD pipelines with GitHub Actions and Bash scripts for build, validation, and deployment, reducing manual delivery steps.
* Used Linux daily across development and production-related routines.

---

## Projects 

**Project name:** Sunlog.dev
**Type:** Full stack platform in production
**Link:** [https://sunlog.dev](https://sunlog.dev) 
**Repository:** [https://github.com/LucasNarZ/Sunlog.dev](https://github.com/LucasNarZ/Sunlog.dev)

**Description:**
Devlog platform with automated deployment on AWS, including backend, frontend, and infrastructure.

**Main points:**

* CI/CD with GitHub Actions
* Containerization with Docker
* Reverse proxy with Nginx
* Monitoring with Prometheus and Grafana
* Backend with NestJS + PostgreSQL
* Frontend with Next.js
* 100 unit tests
* 33 HTTP Endpoints

**Project name:** PocScript
**Type:** Compiler written in C
**Repository:** [https://github.com/LucasNarZ/PocScript](https://github.com/LucasNarZ/PocScript)

**Description:**
Built **PocScript**, a study programming language and compiler implemented in C. The project covers the full compilation pipeline from source code tokenization to AST generation, semantic analysis, internal IR lowering, LLVM IR emission, and final executable generation.
Key highlights:
- Implemented a staged compiler architecture with separate lexer, parser, semantic analyzer, IR builder, and LLVM IR printer.
- Designed semantic validation for scopes, declarations, types, function calls, returns, loop control, arrays, pointers, and external functions.
- Built support for core language features including functions, global and local variables, primitive types, arrays, pointers, control flow, function calls, and compound assignments.
- Generated executable programs by compiling emitted LLVM IR, assembling a custom runtime, and linking without libc.
- Developed a small runtime layer with `_start`, Linux syscall-backed primitives, and stdlib-like helpers such as `strlen`, `strcmp`, `memcpy`, and `puts`.
- Added 196 (unit and integration) tests covering lexer, parser, semantic analysis, IR generation, IR printing, runtime, and stdlib behavior.
Technologies: `C`, `LLVM IR`, `NASM`, `Make`, `Linux syscalls`, `Compiler Design`

**Project name:** PCBuilderBR
**Type:** Fullstack application using python
**Link:** [https://pcbuilderbr.com](https://pcbuilderbr.com) 
**Repository:** [https://github.com/LucasNarZ/PCBuilderBR](https://github.com/LucasNarZ/PCBuilderBR)

**Description:**
Full stack project with a FastAPI and PostgreSQL backend for component selection,
total build price calculation, and compatibility analysis between CPU, motherboard,
RAM, GPU, PSU, cooler, and case.
Technologies: FastAPI, Pydantic, PostgreSQL,
Docker, React, Vite, TailwindCSS, Axios
Includes technical rules for socket, chipset, DDR, TDP, connectors, and clearance,
plus a daily worker for price updates from stores such as Kabum, Pichau, and Amazon.

---

## Skills (Organized by Area)

**Backend:**

* Node.js, TypeScript, Python
* NestJS, FastAPI
* PostgreSQL, MySQL, DynamoDB

**Cloud & DevOps:**

* AWS (Lambda, S3, SQS, EC2, RDS, IoT Core, CloudWatch)
* Terraform (IaC)
* CI/CD (GitHub Actions)
* Docker
* Linux (daily use)
* Bash (automation and scripts)
* Monitoring (Prometheus, Grafana)

**Frontend:**

* React, Next.js
* TailwindCSS

---

## Education

**Program:** Bachelor's Degree in Computer Science
**Institution:** PUCPR
**Period:** 02/2025 - 12/2028

**Main subjects:**

* Algorithms and Data Structures
* Object-Oriented Programming
* Mathematical Logic
* Operating Systems
* Computer Networks
* Information Security
* Systems Performance
* Calculus

---

## Languages

* Portuguese: Native
* English: Professional proficiency
