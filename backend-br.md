# Lucas Narloch Zabla

## Desenvolvedor Backend Júnior | Python, APIs REST, AWS

Desenvolvedor Backend Júnior com experiência em produção no desenvolvimento de APIs REST, integrações entre serviços e rotinas backend em ambientes AWS. Trabalho com Python, Node.js e TypeScript, com vivência em arquiteturas serverless, mensageria assíncrona, CI/CD e Infraestrutura como Código. Tenho foco em entregar aplicações confiáveis, com boa manutenção e evolução contínua em ambiente real.

- Telefone: +55 (41) 98719-8655
- Email: lucasnarloch123@gmail.com
- GitHub: https://github.com/LucasNarZ
- LinkedIn: https://www.linkedin.com/in/lucasnarloch
- Portfolio: https://lucasnarz.github.io/Portfolio/

## Competências

- **Backend**: Python, Node.js, TypeScript, APIs REST, FastAPI, NestJS, Sequelize, Pydantic, Jest
- **Bancos de Dados**: PostgreSQL, MySQL, DynamoDB, modelagem relacional, consultas SQL
- **Cloud & Infra**: AWS Lambda, SQS, S3, AWS IoT Core, CloudWatch, Terraform, Docker, GitHub Actions, CI/CD
- **Monitoramento**: Prometheus, Grafana, troubleshooting, análise de métricas

## Experiência

### Desenvolvedor Backend
**SmartLy Fabricação de Dispositivos Inteligentes Ltda.**  
09/2024 – Atual

- Desenvolvi endpoint para migração de dados entre dispositivos IoT, integrando 4 serviços (MySQL, DynamoDB, S3 e AWS IoT Core) via MQTT.
- Implementei testes automatizados para APIs em FastAPI com pytest, incluindo 20 testes de integração com Testcontainers e 50 testes unitários, aumentando a segurança nas alterações e reduzindo risco de regressões.
- Desenvolvi um worker agendado por cron para atualização automática de horários de pôr do sol, identificando rotinas afetadas, persistindo as mudanças no banco de dados e enviando atualizações via MQTT para os dispositivos.
- Implementei processamento assíncrono com SQS para desacoplamento de fluxos críticos e maior estabilidade nas requisições.
- Otimizei funções AWS Lambda em Python, reduzindo a média de erros a cada 5 minutos de 113 para 5, uma redução de 95,6%, aumentando a confiabilidade do sistema em produção.
- Estruturei infraestrutura como código com Terraform e automatizei deploys com GitHub Actions, substituindo processos manuais.
- Contribuí para a redução de custos em cloud (~20%) a partir da análise de métricas e identificação de recursos ociosos.

## Projetos

### Sunlog.dev - Plataforma de Devlogs por Projeto

Plataforma full stack onde a entidade central é **Projeto**, permitindo associar **devlogs versionados** para registrar progresso e decisões técnicas. Inclui APIs REST, modelagem relacional, autenticação e monitoramento com métricas.

- **Tecnologias**: NestJS, Sequelize, Next.js, TailwindCSS, PostgreSQL, Jest, AWS, GitHub Actions, Docker, Prometheus, Grafana
- Código: https://github.com/LucasNarZ/Sunlog.dev
- Live demo: https://sunlog.dev

### PCBuilderBR - Backend para montagem de PCs com validação de compatibilidade

Projeto full stack com backend em FastAPI e PostgreSQL para seleção de componentes, cálculo de preço total da build e análise de compatibilidade entre CPU, placa-mãe, RAM, GPU, PSU, cooler e gabinete.

- **Tecnologias**: FastAPI, Pydantic, PostgreSQL, Docker, React, Vite, TailwindCSS, Axios
- Inclui regras técnicas para socket, chipset, DDR, TDP, conectores e clearance, além de worker diário para atualização de preços em lojas como Kabum, Pichau e Amazon.
- Código: https://github.com/LucasNarZ/PCBuilderBR
- Live demo: https://pcbuilderbr.com

## Formação

### PUCPR - Bacharelado em Ciência da Computação
02/2025 - 12/2028

- Bolsista integral (100%)
- Algoritmos, Estruturas de Dados, Lógica Matemática, Desenvolvimento Web, Java, Modelagem de BD

### CEEP - Técnico em Eletrônica
02/2022 - 12/2024

- KiCad, design de PCB, eletrônica analógica

## Idiomas

- **Português**: Nativo
- **Inglês**: Uso profissional — leitura e escuta avançadas; conversação e escrita intermediárias

## Certificados

### Fundamentals of Database Engineering - Udemy

- Índices (B-Tree/B+Tree), paginação, particionamento, transações e funcionamento interno de bancos de dados
- Instrutor: Hussein Nasser
- Conclusão: Set/2025
