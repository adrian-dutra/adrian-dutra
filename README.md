<div align="center">

# Hi, I'm Adriano 👋

**Backend Developer** building integrations, payments and fiscal automation systems

Python · Django · Node.js · Kotlin · Oracle · PostgreSQL · RabbitMQ · Docker

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2EyLjA2MiAyLjA2MiAwIDEgMSAwLTQuMTI1IDIuMDYyIDIuMDYyIDAgMCAxIDAgNC4xMjV6TTcuMTE5IDIwLjQ1MkgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPg==)](https://www.linkedin.com/in/adriano-ara%C3%BAjo-dutra-465043200/)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:adrianodutra.dev@gmail.com)

</div>

<details>
<summary>🇧🇷 <b>Português: clique para expandir</b></summary>

## 💼 Sobre

Sou Desenvolvedor Backend na **Cardway**, trabalhando em sistemas de back-office, pagamentos e integração com marketplaces para uma empresa brasileira de cartões e meios de pagamento. Entrei como estagiário em abril de 2024 e fui efetivado como Desenvolvedor Júnior em março de 2025, entregando mudanças em 20 serviços de produção construídos principalmente com Python/Django, Node.js e Kotlin sobre Oracle e PostgreSQL.
A maior parte do meu trabalho conecta sistemas internos a plataformas externas: marketplaces, um bureau de crédito, a SEFAZ e ferramentas de atendimento.

## 📈 Impacto na Cardway

<!-- IMPACT-PT:START -->
![Contribuições](https://img.shields.io/badge/Contribui%C3%A7%C3%B5es_no_GitLab-2.283-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Commits](https://img.shields.io/badge/Commits-682-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Merge Requests](https://img.shields.io/badge/Merge_Requests-514-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Mergeados](https://img.shields.io/badge/Mergeados-488-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Code Reviews](https://img.shields.io/badge/Code_Reviews-45-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Dias ativos](https://img.shields.io/badge/Dias_ativos-342-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Projetos](https://img.shields.io/badge/Projetos-20-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)

### Destaques

- **Construí** do zero um serviço automatizado de **GNRE** (guia de recolhimento de tributos interestaduais) integrado à **SEFAZ** via web services SOAP e certificado digital, cobrindo schemas XML, envio em lote, consulta de resultado, monitoramento de erros e sincronização com o ERP (46 commits).
- **Entreguei** integrações com marketplaces de ponta a ponta: a integração completa com a **Shopee** (pedidos, status logístico, etiquetas de envio com NF-e, webhooks) e um novo módulo no **Mercado Livre** para venda de produtos digitais (eSIM) com proteção contra venda abaixo do custo (66 commits, 46 merge requests).
- **Reduzi** as requisições de token de autenticação em uma integração de pagamentos **de mais de 4.000 para 1 por execução**, e fortaleci integrações com parceiros de repasses, parcelas e liquidação de recebíveis com paginação, schedulers, upserts e correções de pool de conexões.

<sub>Meu trabalho fica em um GitLab privado e self-hosted, por isso não aparece neste perfil do GitHub. Números agregados desde abril de 2024. Última atualização: outubro de 2026.</sub>
<!-- IMPACT-PT:END -->

## 🧩 O que eu construo

- **🔌 Integrações externas**: APIs REST e webhooks conectando sistemas internos a marketplaces (Shopee, Mercado Livre), a um bureau de crédito (Serasa), a uma plataforma de notas fiscais eletrônicas e a ferramentas de atendimento (Zendesk e um chatbot no Botpress).
- **🧾 Automação fiscal e tributária**: emissão de GNRE pela SEFAZ (SOAP, XML, certificado digital), download e filtragem de NF-e/CT-e e geração da DIMP.
- **💳 Pagamentos e recebíveis**: pipelines de repasses, parcelas, transações e agenda de liquidação de recebíveis, com schedulers, paginação e atualizações idempotentes em Node.js e Kotlin/Spring.
- **⚙️ Processamento assíncrono e serviços internos**: jobs em background com RabbitMQ e Celery, um gateway web seguro para os servidores FTPS da empresa e entrega containerizada com Docker e Jenkins.

## 🔭 Explorando agora

- Evoluir a arquitetura e a escalabilidade de sistemas backend
- Construir integrações confiáveis e observáveis entre sistemas
- Sistemas distribuídos e processamento assíncrono

<sub>Stack e contato logo abaixo, na versão em inglês.</sub>

</details>

---

## 💼 About

I'm a Backend Developer at **Cardway**, working on back-office, payments and marketplace integration systems for a Brazilian card and payments company. I joined as an intern in April 2024 and was promoted to Junior Developer in March 2025, shipping changes across 20 production services built mostly with Python/Django, Node.js and Kotlin on top of Oracle and PostgreSQL.
Most of my work connects internal systems to external platforms: marketplaces, a credit bureau, the state tax authority (SEFAZ) and customer support tools.

---

## 📈 Impact at Cardway

<!-- IMPACT:START -->
![Contributions](https://img.shields.io/badge/GitLab_Contributions-2,283-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Commits](https://img.shields.io/badge/Commits-682-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Merge Requests](https://img.shields.io/badge/Merge_Requests-514-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Merged](https://img.shields.io/badge/Merged-488-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Code Reviews](https://img.shields.io/badge/Code_Reviews-45-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Active Days](https://img.shields.io/badge/Active_Days-342-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Projects](https://img.shields.io/badge/Projects-20-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)

### Highlights

- **Built** from scratch an automated **GNRE** (interstate tax payment slip) service integrated with **SEFAZ** through SOAP web services and digital certificates, covering XML schemas, batch submission, result polling, error monitoring and ERP sync (46 commits).
- **Delivered** marketplace integrations end to end: a full **Shopee** integration (orders, logistics status, invoice-based shipping labels, webhooks) and a new **Mercado Livre** module for selling digital products (eSIM) with below-cost price protection (66 commits, 46 merge requests).
- **Cut** authentication token requests in a payments integration **from 4,000+ to 1 per run**, and hardened partner integrations for transfers, installments and receivables settlement with pagination, schedulers, upserts and connection-pool fixes.

<sub>My work lives in a private, self-hosted GitLab, so it doesn't show up on this GitHub profile. Numbers are aggregated since April 2024. Last updated: October 2026.</sub>
<!-- IMPACT:END -->

---

## 🛠 Tech Stack

### Backend
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)

### Messaging & Async Processing
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)

### Databases
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)

---

## 🧩 What I Build

- **🔌 External integrations**: REST APIs and webhooks connecting internal systems to marketplaces (Shopee, Mercado Livre), a credit bureau (Serasa), an e-invoice platform and customer support tools (Zendesk and a Botpress chatbot).
- **🧾 Fiscal and tax automation**: GNRE issuing through SEFAZ (SOAP, XML, digital certificates), NF-e/CT-e download and filtering, and DIMP tax report generation.
- **💳 Payments and receivables**: pipelines for transfers, installments, transactions and the receivables settlement schedule, with schedulers, pagination and idempotent updates in Node.js and Kotlin/Spring.
- **⚙️ Async processing and internal services**: background jobs with RabbitMQ and Celery, a secure web gateway for the company's FTPS servers, and containerized delivery with Docker and Jenkins.

---

## 🔭 Currently Exploring

- Improving backend architecture and scalability
- Building reliable, observable integrations between systems
- Distributed systems and asynchronous processing

---

## 📫 Contact

- LinkedIn: [adriano-araújo-dutra](https://www.linkedin.com/in/adriano-ara%C3%BAjo-dutra-465043200/)
- Email: [adrianodutra.dev@gmail.com](mailto:adrianodutra.dev@gmail.com)
