# Lucas Narloch Zabla

## DevOps & Cloud Engineer Júnior | AWS, Linux, Docker, CI/CD

Profissional com foco em DevOps e Cloud, com experiência prática em infraestrutura AWS, Linux, automação de deploys e operação de aplicações em produção. Atuo com Terraform, Docker, GitHub Actions, Bash, observabilidade e configuração de servidores, incluindo publicação de projetos em VPS com reverse proxy, pipelines CI/CD e monitoramento. Possuo base sólida em backend, o que facilita integração entre aplicação, infraestrutura e rotina operacional.

- Telefone: +55 (41) 98719-8655
- Email: lucasnarloch123@gmail.com
- GitHub: https://github.com/LucasNarZ
- LinkedIn: https://www.linkedin.com/in/lucasnarloch
- Portfolio: https://lucasnarz.github.io/Portfolio/

## Competências

- **Cloud & IaC**: AWS (EC2, Lambda, SQS, S3, DynamoDB, IoT Core, CloudWatch, ECR), Terraform
- **CI/CD & Automação**: GitHub Actions, Bash scripting, build e deploy automatizados, pipelines de entrega contínua
- **Servidores & Containers**: Linux, Docker, VPS, Caddy, Nginx, reverse proxy, publicação de aplicações containerizadas
- **Observabilidade & Operação**: Prometheus, Grafana, CloudWatch, análise de logs, troubleshooting, confiabilidade
- **Backend de Apoio**: Python, Node.js, TypeScript, FastAPI, NestJS, PostgreSQL, MySQL

## Experiência

### Desenvolvedor Backend
**SmartLy Fabricação de Dispositivos Inteligentes Ltda.**  
09/2024 – Atual

- Estruturei infraestrutura como código com Terraform, migrando ambientes gerenciados manualmente para um modelo versionado, reproduzível e mais seguro para evolução.
- Automatizei pipelines CI/CD com GitHub Actions e scripts Bash para build, validação e deploy, reduzindo etapas manuais na entrega.
- Introduzi processamento assíncrono com SQS, desacoplando fluxos críticos e melhorando a escalabilidade.
- Otimizei funções AWS Lambda em Python, reduzindo a média de erros de 113 para 5 a cada 5 minutos (~95%).
- Reduzi custos de infraestrutura em ~20% ao identificar e eliminar recursos ociosos.
- Atuei na análise de logs e métricas com CloudWatch, identificando gargalos, falhas em produção e oportunidades de melhoria operacional.
- Desenvolvi integrações entre serviços (MySQL, DynamoDB, S3, IoT Core) garantindo consistência de dados.
- Criei utilitários com Docker para simulação de ambientes locais e testes de integração.

## Projetos

### Sunlog.dev - Plataforma de Devlogs em Produção

Plataforma full stack publicada em VPS com stack containerizada, deploy automatizado por pipeline e operação com foco em observabilidade. Configurei reverse proxy em alto nível com Caddy e Nginx internamente na aplicação, além de pipeline com build de imagem no Amazon ECR antes do deploy.

- **Tecnologias**: Terraform, Docker, GitHub Actions, AWS, Amazon ECR, Caddy, Nginx, Prometheus, Grafana, NestJS, PostgreSQL, Next.js
- Código: https://github.com/LucasNarZ/Sunlog.dev
- Live demo: https://sunlog.dev

### PCBuilderBR - Plataforma containerizada com atualização diária de ofertas

Plataforma full stack publicada em VPS com frontend e backend containerizados, proxy reverso com Caddy em alto nível e Nginx interno para servir a aplicação. O ambiente inclui pipeline de deploy e rotina operacional para atualização diária de preços.

- **Tecnologias**: Docker, GitHub Actions, Caddy, Nginx, FastAPI, PostgreSQL, React, Vite, TailwindCSS, Pydantic
- Inclui worker diário para coleta e atualização de preços em múltiplas lojas e lógica de validação técnica para socket, TDP, conectores e dimensões físicas dos componentes.
- Código: https://github.com/LucasNarZ/PCBuilderBR
- Live demo: https://pcbuilderbr.com

## Formação

### PUCPR - Bacharelado em Ciência da Computação
02/2025 - 12/2028

- Bolsista integral (100%)
- Foco em Estruturas de Dados, Performance de Sistemas, Segurança da Informação e Modelagem de Banco de Dados

### CEEP - Técnico em Eletrônica
02/2022 - 12/2024

- KiCad, design de PCB, eletrônica analógica, sistemas embarcados

## Idiomas

- **Português**: Nativo
- **Inglês**: Intermediário (leitura e comunicação técnica)

## Certificados

### Fundamentals of Database Engineering - Udemy

- Índices (B-Tree/B+Tree), paginação, particionamento, sharding, replicação e transações ACID
- Instrutor: Hussein Nasser
- Conclusão: Set/2025
