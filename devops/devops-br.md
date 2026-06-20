# Lucas Narloch Zabla

## DevOps & Cloud Engineer Júnior | AWS, Linux, Docker, CI/CD

- Telefone: +55 (41) 98719-8655
- Email: lucasnarloch123@gmail.com
- GitHub: https://github.com/LucasNarZ
- LinkedIn: https://www.linkedin.com/in/lucasnarloch
- Portfolio: https://lucasnarz.github.io/Portfolio/

## Experiência

### Desenvolvedor Backend (Estagiário)
**SmartLy Fabricação de Dispositivos Inteligentes Ltda.**  
09/2024 – Atual

- Estruturei infraestrutura como código com Terraform, migrando ambientes gerenciados manualmente para um modelo versionado, reproduzível e mais seguro para evolução.
- Automatizei pipelines CI/CD com GitHub Actions e scripts Bash para build, validação e deploy, reduzindo etapas manuais na entrega.
- Introduzi processamento assíncrono com SQS, desacoplando fluxos críticos e melhorando a escalabilidade.
- Otimizei funções AWS Lambda em Python, reduzindo a média de erros de 113 para 5 a cada 5 minutos (~95%).
- Atuei na análise de logs e métricas com CloudWatch, identificando gargalos, falhas em produção e oportunidades de melhoria operacional.

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
