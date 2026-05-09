## 🎯 Objetivo

Maximizar a taxa de entrevistas ajustando currículos de forma estratégica para cada vaga, alinhando:

- Palavras-chave da vaga e ATS
- Expectativa do recrutador
- Nível percebido: Estágio, Júnior ou Pleno
- Stack, responsabilidades e contexto da empresa
- Evidências reais da experiência do candidato

O objetivo NÃO é criar o currículo mais completo possível.

O objetivo é criar o currículo **mais relevante possível para a vaga específica**.

Um bom currículo customizado deve fazer o recrutador pensar rapidamente:

> “Esse candidato parece feito para esta vaga.”

---

## 🧠 Princípios Fundamentais

### 1. Relevância > Completude

O currículo não deve conter tudo que o candidato sabe ou já fez.

Deve conter apenas o que aumenta a chance de entrevista para aquela vaga.

Remover, reduzir ou esconder qualquer item que não ajude diretamente no encaixe, mesmo que seja tecnicamente bom.

Exemplos:

- Se a vaga não pede IaC, Terraform não deve ocupar destaque.
- Se a vaga não pede AWS, cloud deve aparecer apenas como diferencial secundário.
- Se a vaga é backend básico, a seção de competências deve focar só em backend e banco.
- Se a vaga não pede frontend, frontend deve ser removido ou aparecer apenas em projeto.
- Se a vaga é Python/FastAPI, projeto Node/NestJS pode ser reduzido ou removido.
- Se a vaga é Node/NestJS, projeto Python/FastAPI pode ser reduzido ou removido.
- Se o certificado não reforça a vaga, remover.
- Se uma tecnologia gera ruído ou muda a percepção do perfil, remover ou descer.

Currículo bom não é inventário. Currículo bom é filtro.

---

### 2. Alinhamento > Qualidade Técnica

Um currículo genérico forte é inferior a um currículo mediano altamente alinhado com a vaga.

Sempre priorizar:

- Stack mencionada na vaga
- Responsabilidades descritas
- Tipo de sistema: web, APIs, dados, cloud, integrações, automações
- Nível esperado: estágio, júnior ou pleno
- Termos exatos usados na descrição da vaga

Se uma informação é tecnicamente impressionante, mas não reforça o fit da vaga, ela deve perder espaço.

---

### 3. O recrutador bate o olho por 10 segundos

O topo do currículo precisa responder rapidamente:

- Esse candidato usa as tecnologias que eu pedi?
- Ele já fez algo parecido?
- Ele parece estar no nível certo?
- Ele está disponível para o formato/local da vaga?

Se a resposta não for óbvia, o currículo deve ser refeito.

O currículo deve ser claro para RH antes de ser impressionante para técnico.

---

### 4. Nunca gerar ruído desnecessário

Ruído é qualquer informação que distrai, confunde ou enfraquece o posicionamento.

Exemplos de ruído:

- Tecnologias não pedidas pela vaga ocupando destaque.
- Muitos tópicos diferentes competindo por atenção.
- Bullet técnico demais para uma vaga júnior simples.
- Ênfase em DevOps para vaga de backend web.
- Ênfase em frontend para vaga backend.
- Certificado pouco relacionado.
- Projeto desalinhado com a stack da vaga.
- Linguagem que parece sênior demais para vaga júnior.
- Descrições longas que escondem o que a vaga realmente pede.
- Seção de competências grande demais, parecendo inventário técnico.

Regra prática:

> Se uma informação não ajuda o recrutador a dizer “sim”, ela provavelmente atrapalha.

---

### 5. Competências devem ser enxutas

A seção de competências deve ser curta, objetiva e altamente alinhada à vaga.

Ela NÃO deve listar tudo que o candidato sabe.

Ela deve mostrar rapidamente:

- linguagens principais;
- frameworks principais;
- bancos de dados relevantes;
- ferramentas essenciais, apenas se a vaga pedir ou valorizar.

Evitar colocar em competências:

- manutenção de funcionalidades;
- revisão de código;
- boas práticas;
- troubleshooting;
- análise de métricas;
- design de software;
- system design;
- colaboração;
- entrega de valor;
- termos comportamentais.

Esses pontos devem aparecer no resumo ou na experiência, não como competências técnicas.

---

## 🧩 Regras para Competências

### Vaga backend básica

Usar apenas blocos essenciais:

```text
Backend: Python, FastAPI, Node.js, NestJS, APIs REST
Bancos de Dados: MySQL, PostgreSQL, DynamoDB
````

Se a vaga pedir Java/Spring:

```text
Backend: Java, Spring Boot básico, Python, APIs REST
Bancos de Dados: MySQL, PostgreSQL, DynamoDB
```

---

### Vaga backend com testes

Adicionar testes apenas se for relevante:

```text
Backend: Python, FastAPI, APIs REST
Bancos de Dados: MySQL, PostgreSQL
Testes: pytest, Testcontainers, Jest
```

---

### Vaga backend com cloud, Docker ou CI/CD

Adicionar ferramentas:

```text
Backend: Python, FastAPI, APIs REST
Bancos de Dados: MySQL, PostgreSQL, DynamoDB
Ferramentas: AWS, Docker, GitHub Actions, CI/CD
```

Se a vaga pedir Terraform ou IaC:

```text
Ferramentas: AWS, Docker, GitHub Actions, Terraform, CI/CD
```

Não colocar Terraform se a vaga não pedir IaC, cloud avançado ou infraestrutura.

---

### Vaga backend com observabilidade

Adicionar observabilidade apenas se a vaga pedir:

```text
Backend: Python, FastAPI, APIs REST
Bancos de Dados: MySQL, PostgreSQL, DynamoDB
Ferramentas: AWS, Docker, GitHub Actions
Observabilidade: CloudWatch, Prometheus, Grafana
```

---

### Vaga fullstack

Backend sempre vem antes, se o alvo principal ainda for backend.

```text
Backend: Node.js, TypeScript, NestJS, APIs REST
Bancos de Dados: PostgreSQL, MySQL
Frontend: React, Next.js, TailwindCSS
Ferramentas: Docker, GitHub Actions
```

Frontend só entra se a vaga pedir explicitamente frontend, fullstack, React, Next.js ou TypeScript no frontend.

---

### Vaga frontend/fullstack com mais peso em frontend

```text
Frontend: React, Next.js, TypeScript, TailwindCSS
Backend: Node.js, NestJS, APIs REST
Bancos de Dados: PostgreSQL, MySQL
Ferramentas: Docker, GitHub Actions
```

---

### Vaga cloud/serverless

```text
Backend: Python, APIs REST, workers assíncronos
Cloud: AWS Lambda, SQS, S3, DynamoDB, CloudWatch
Bancos de Dados: MySQL, PostgreSQL, DynamoDB
Ferramentas: Docker, GitHub Actions, Terraform
```

Usar esse formato apenas se a vaga realmente puxar para cloud/serverless.

---

## 🧩 Estrutura Base do Currículo

### Regras obrigatórias para currículos gerados

Ao gerar ou customizar currículos neste diretório, nunca adicionar tecnologias, frameworks, ferramentas, responsabilidades, experiências, certificados ou competências que não estejam mencionados em pelo menos um currículo já existente no diretório.

Se uma tecnologia aparece na vaga, mas não aparece em nenhum currículo existente, ela deve ser omitida ou tratada apenas como contexto da vaga, nunca como conhecimento, experiência ou competência do candidato.

Não inferir conhecimento por proximidade técnica. Exemplo: saber Python/FastAPI não autoriza colocar Django; saber React não autoriza colocar Next.js se isso não estiver em currículo existente; saber AWS Lambda não autoriza colocar serviços AWS não mencionados.

Currículos HTML gerados devem seguir a mesma formatação, estrutura visual e estilo do `TEMPLATE.html`, salvo instrução explícita em contrário. Não criar layouts novos, colunas laterais, temas visuais diferentes ou estilos autorais quando o pedido for gerar currículo.

Antes de finalizar, revisar especificamente se há alguma tecnologia ou afirmação que não tenha fonte em currículo existente do diretório. Se houver, remover.

### 1. Título

Formato:

```text
Cargo alvo | principais tecnologias da vaga
```

Exemplos:

```text
Desenvolvedor Backend Júnior | Python, FastAPI, PostgreSQL
```

```text
Desenvolvedor Backend Júnior | Node.js, TypeScript, NestJS
```

```text
Desenvolvedor Full Stack Júnior | React, Node.js, APIs REST
```

Nunca usar título genérico quando a vaga é específica.

O título deve ser ajustado para a vaga.

---

### 2. Resumo

O resumo é o bloco mais importante do currículo.

Deve conter:

* Cargo alvo
* Stack principal da vaga
* Tipo de sistema ou problema
* Experiência prática relevante
* Disponibilidade/local quando relevante
* Sinal de aprendizado e adaptação

Evitar:

* Lista longa de tecnologias
* Buzzwords genéricas
* Exagero técnico
* Termos não relacionados à vaga

Modelo:

```text
Desenvolvedor backend com experiência prática em APIs REST, integrações e banco de dados em ambiente de produção. Atuo principalmente com [stack da vaga], desenvolvendo features, correções, testes e rotinas backend. Busco vaga [nível/formato] com foco em [principais responsabilidades da vaga].
```

---

### 3. Competências

A seção de competências deve ser uma das partes mais curtas do currículo.

Regras:

* Usar de 2 a 4 blocos no máximo.
* Cada bloco deve ter tecnologias objetivas.
* Não listar conceitos comportamentais.
* Não listar responsabilidades como competência.
* Não listar tecnologias que não ajudam na vaga.
* Não tentar mostrar tudo.
* Ordenar os blocos conforme a vaga.

Ordem recomendada para vaga backend simples:

```text
Backend
Bancos de Dados
```

Ordem recomendada para vaga backend com ferramentas:

```text
Backend
Bancos de Dados
Ferramentas
```

Ordem recomendada para vaga fullstack:

```text
Backend
Bancos de Dados
Frontend
Ferramentas
```

Ordem recomendada para vaga cloud:

```text
Backend
Cloud
Bancos de Dados
Ferramentas
```

---

### 4. Experiência

Cada bullet deve seguir:

```text
ação + tecnologia/contexto + resultado/impacto
```

Exemplo:

```text
Desenvolvi APIs REST em Python com FastAPI para integração entre serviços internos.
```

Critérios para escolher bullets:

* A vaga pede isso?
* Esse bullet prova experiência real no problema da vaga?
* Esse bullet usa palavras-chave importantes?
* Esse bullet reforça o nível correto?
* Esse bullet reduz ou aumenta ruído?

Se o bullet não reforça a vaga, remover ou substituir.

Não manter bullet apenas porque ele é tecnicamente bom.

---

### 5. Projetos

Projetos devem ser escolhidos por aderência à vaga, não por orgulho pessoal.

Regra principal:

> Usar apenas um projeto, exceto quando a vaga pedir explicitamente stacks ou contextos que os dois projetos cobrem bem.

Exemplos:

* Vaga Python/FastAPI → usar PCBuilderBR.
* Vaga Node/NestJS/TypeScript → usar Sunlog.dev.
* Vaga fullstack React + backend → usar Sunlog.dev.
* Vaga backend com regras de negócio → usar PCBuilderBR.
* Vaga que pede Python e Node → pode manter os dois, se houver espaço.
* Vaga genérica backend → escolher o projeto que melhor conversa com a stack principal.

O projeto deve mostrar:

* stack relevante;
* problema resolvido;
* backend/API/banco/testes/deploy quando fizer sentido;
* link para código e demo se existirem.

Remover ou reduzir projetos desalinhados.

Se houver dúvida, manter apenas o projeto mais alinhado.

---

### 6. Formação, Idiomas e Certificados

Manter formação de forma objetiva.

Certificados só devem aparecer se reforçarem diretamente a vaga.

Exemplos:

* Vaga com SQL, modelagem, performance de queries, banco relacional ou dados → certificado de Database Engineering pode ficar.
* Vaga backend genérica → certificado pode sair.
* Vaga cloud → certificado de banco pode sair se ocupar espaço.
* Vaga Node/React → certificado de banco geralmente deve sair.
* Vaga Python/FastAPI com banco forte → certificado pode ficar se houver espaço.

Não manter certificado por apego.

---

## 🔄 Processo de Customização por Vaga

### Etapa 1 — Ler a vaga e extrair sinais

Identificar:

* Cargo
* Nível
* Stack obrigatória
* Stack desejável
* Responsabilidades
* Tipo de produto/sistema
* Formato: remoto, híbrido, presencial
* Localidade
* Palavras repetidas
* O que a empresa parece valorizar

---

### Etapa 2 — Separar o que é essencial, desejável e ruído

Classificar cada item do currículo em:

#### Essencial

A vaga pede diretamente ou o item prova fit forte.

#### Desejável

Ajuda, mas não deve ocupar destaque.

#### Ruído

Não ajuda ou pode confundir o posicionamento.

Tudo que for ruído deve ser removido, reduzido ou movido para baixo.

---

### Etapa 3 — Classificar a vaga

Tipo:

* Backend
* Fullstack
* DevOps/Cloud
* Data
* QA/Testes
* Produto interno
* Consultoria

Nível:

* Estágio
* Júnior
* Pleno

Ajuste por nível:

* Júnior → clareza, execução, aprendizado, APIs, bugs, testes, banco
* Pleno → autonomia, impacto, arquitetura, ownership, performance
* Estágio → base técnica, projetos, aprendizado, colaboração

---

### Etapa 4 — Ajustar título

O título deve usar o cargo e as tecnologias principais da vaga.

Exemplo:

```text
Desenvolvedor Backend Júnior | Python, FastAPI, PostgreSQL
```

Evitar título amplo se a vaga é específica.

---

### Etapa 5 — Reescrever resumo

Focar em:

* Stack da vaga
* Atividades da vaga
* Experiência real relacionada
* Nível correto
* Local/formato se relevante

O resumo deve parecer escrito para aquela vaga.

---

### Etapa 6 — Ajustar competências

Criar uma seção curta, com poucos blocos.

Regra:

* Backend básico → `Backend` e `Bancos de Dados`
* Backend com cloud/CI/CD/Docker → adicionar `Ferramentas`
* Backend com observabilidade → adicionar `Observabilidade`
* Fullstack/frontend → adicionar `Frontend`
* Cloud/serverless → usar `Cloud` ou `Ferramentas`, conforme a vaga

Não incluir blocos só para mostrar conhecimento.

Não incluir tecnologias que não aparecem na vaga ou não reforçam o fit.

---

### Etapa 7 — Ajustar experiência

Selecionar apenas bullets relevantes.

Para cada bullet, perguntar:

* Isso ajuda nesta vaga?
* Isso usa palavras-chave importantes?
* Isso mostra experiência prática?
* Isso está no nível certo?
* Isso compete com informações mais importantes?

Se não, remover.

---

### Etapa 8 — Escolher projeto

Selecionar o projeto mais alinhado com a vaga.

Manter dois projetos apenas se a vaga justificar claramente.

Se um projeto não conversa com a vaga, remover.

---

### Etapa 9 — Avaliar certificado

Certificado só entra se for diretamente relevante.

Perguntar:

* A vaga enfatiza banco de dados?
* A vaga pede SQL, modelagem, performance, transações ou dados?
* O certificado reforça um requisito importante?
* Há espaço sem deixar o currículo poluído?

Se não, remover.

---

### Etapa 10 — Cortar ruído

Antes da versão final, fazer uma passada específica só para remover ruído.

Perguntar:

* O que aqui não foi pedido?
* O que aqui distrai?
* O que aqui parece técnico demais para a vaga?
* O que aqui parece fora da stack?
* O que aqui ocupa espaço sem aumentar chance de entrevista?
* O que aqui eu coloquei só porque acho legal?
* A seção de competências está curta o suficiente?
* Há mais de um projeto sem necessidade?
* O certificado realmente ajuda?

Remover sem apego.

---

### Etapa 11 — Revisão final

Checklist:

* Esse currículo parece feito para esta vaga?
* O topo responde a vaga em 10 segundos?
* As tecnologias principais aparecem no título/resumo/competências?
* A seção de competências está enxuta?
* A experiência prova algo parecido com o que a vaga pede?
* O projeto escolhido reforça a stack da vaga?
* Há ruído técnico desnecessário?
* O nível percebido está correto?
* O currículo está claro para RH?
* O currículo continua verdadeiro?

Se não, refazer.

---

## ⚠️ Erros Críticos

### ❌ Currículo inventário

Listar tudo que o candidato sabe.

Correção:

> Listar apenas o que aumenta o fit com a vaga.

---

### ❌ Competências grandes demais

Competências não devem parecer uma lista completa de tecnologias.

Ruim:

```text
Backend: APIs REST, FastAPI, NestJS, testes automatizados, manutenção de funcionalidades, design de software, revisão de código, boas práticas, troubleshooting
```

Melhor:

```text
Backend: Python, FastAPI, Node.js, NestJS, APIs REST
Bancos de Dados: MySQL, PostgreSQL, DynamoDB
```

---

### ❌ Currículo genérico

Usar o mesmo currículo para todas as vagas.

Correção:

> Usar versões base e customizar para vagas boas.

---

### ❌ Excesso de DevOps em vaga backend web

Terraform, CI/CD, cloud e infra podem ser diferenciais, mas não devem dominar vaga de API/CRUD/backend.

---

### ❌ Excesso de frontend em vaga backend

Frontend só deve aparecer se a vaga pedir fullstack ou se o projeto precisar de contexto.

---

### ❌ Dois projetos sem necessidade

Manter dois projetos pode gerar ruído.

Correção:

> Usar um projeto principal, a menos que a vaga justifique claramente os dois.

---

### ❌ Certificado desalinhado

Certificado só deve aparecer se reforçar um requisito relevante.

---

### ❌ Excesso de senioridade em vaga júnior

Evitar linguagem que pareça liderança técnica, arquitetura ampla ou responsabilidade incompatível com júnior.

---

### ❌ Falta de palavras-chave

Se a vaga pede FastAPI, PostgreSQL e Docker, esses termos precisam aparecer claramente.

---

### ❌ Foco em tecnologia em vez de problema

Tecnologia deve aparecer ligada a algo feito.

Ruim:

```text
Experiência com AWS Lambda, SQS, DynamoDB e Terraform.
```

Melhor:

```text
Implementei workers assíncronos com AWS Lambda e SQS para processar tarefas fora do fluxo principal da API.
```

---

## 🚀 Estratégia de Aplicação

### 1. Currículos base

Manter versões base para:

* Python/FastAPI
* Node.js/NestJS
* Backend geral
* Cloud/AWS
* Fullstack

Usar a versão mais próxima como ponto de partida.

---

### 2. Customização por prioridade

#### Vaga comum

Usar versão base com ajustes leves.

#### Vaga boa

Customizar título, resumo, competências, experiência e projeto.

#### Vaga muito boa

Customizar profundamente e enviar mensagem junto.

---

### 3. Regra de compatibilidade

Aplicar se:

* Linguagem bate; ou
* Framework bate; ou
* Conceitos principais batem; ou
* Problema da vaga parece parecido com experiência/projeto.

Não precisa bater 100%.

---

### 4. Distribuição ideal

* 60% vagas alinhadas
* 30% vagas parcialmente alinhadas
* 10% vagas acima do nível

---

### 5. Prioridade

Dar mais atenção para:

* Vagas híbridas ou presenciais em Curitiba
* Vagas com poucas candidaturas
* Empresas menores
* Vagas recém-publicadas
* Vagas com stack muito próxima
* Vagas com descrição objetiva
* Vagas fora do “candidatura fácil”

---

## 🧠 Estratégia de Posicionamento

O mesmo candidato pode ser posicionado de formas diferentes.

### Backend

Destacar:

* APIs REST
* Banco de dados
* Integrações
* Testes
* Workers
* Regras de negócio

Reduzir:

* Frontend
* Infra avançada
* Certificados pouco relacionados

Competências típicas:

```text
Backend: Python, FastAPI, APIs REST
Bancos de Dados: MySQL, PostgreSQL
```

---

### Fullstack

Destacar:

* APIs + UI
* Projetos completos
* React/Next.js quando a vaga pedir
* Backend com banco de dados

Reduzir:

* AWS avançado
* Terraform
* Observabilidade complexa

Competências típicas:

```text
Backend: Node.js, TypeScript, NestJS, APIs REST
Bancos de Dados: PostgreSQL, MySQL
Frontend: React, Next.js, TailwindCSS
```

---

### Cloud/Serverless

Destacar:

* AWS Lambda
* SQS
* S3
* DynamoDB
* Terraform
* GitHub Actions
* CloudWatch

Reduzir:

* Frontend
* Projetos sem cloud
* Certificados não relacionados

Competências típicas:

```text
Backend: Python, APIs REST, workers assíncronos
Cloud: AWS Lambda, SQS, S3, DynamoDB, CloudWatch
Ferramentas: Docker, GitHub Actions, Terraform
```

---

### Backend Python

Destacar:

* Python
* FastAPI
* pytest
* SQL
* Docker
* APIs REST
* Integrações

Reduzir:

* Node/NestJS
* Frontend
* Terraform se não pedido

Competências típicas:

```text
Backend: Python, FastAPI, APIs REST
Bancos de Dados: PostgreSQL, MySQL, DynamoDB
```

---

### Backend Node.js

Destacar:

* Node.js
* TypeScript
* NestJS
* PostgreSQL
* APIs REST
* Jest
* Docker

Reduzir:

* Python/FastAPI
* AWS avançado se não pedido
* Certificados pouco relacionados

Competências típicas:

```text
Backend: Node.js, TypeScript, NestJS, APIs REST
Bancos de Dados: PostgreSQL, MySQL
```

---

## 📈 Métrica de Sucesso

Indicador principal:

```text
Taxa de resposta = entrevistas / aplicações
```

Referência:

* 10% → bom
* 20% → excelente
* <5% → provável problema de alinhamento, canal ou posicionamento

Se a taxa ficar abaixo de 5%, revisar:

* Vagas escolhidas
* Título
* Resumo
* Palavras-chave
* Nível percebido
* Excesso de ruído
* Competências grandes demais
* Projetos desalinhados
* Certificados desnecessários
* Localização/formato
* Canal de candidatura

---

## 🔥 Regra Final

Não existe currículo perfeito.

Existe:

> currículo certo para a vaga certa.

E currículo certo não é o que mostra tudo.

É o que mostra **somente o que importa para aquela vaga**.

