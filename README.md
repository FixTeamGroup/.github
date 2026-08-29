<div align="center">

  <a href="https://fixteam.uk" target="_blank">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./assets/banner.png">
      <source media="(prefers-color-scheme: light)" srcset="./assets/banner.png">
      <img src="./assets/banner.png" alt="FixTeam Banner" width="100%" style="max-width: 900px; border-radius: 14px; margin-bottom: 20px; box-shadow: 0 8px 30px rgba(0, 229, 255, 0.25);">
    </picture>
  </a>

  # ⚡ FixTeam
  ### **Engenharia de Software · RPAs Críticos · IA Aplicada & OCR · Plataformas Web**

  <p align="center">
    <a href="https://fixteam.uk"><img src="https://img.shields.io/badge/Website-fixteam.uk-0070f3?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website"></a>
    <a href="mailto:contact@fixteam.uk"><img src="https://img.shields.io/badge/Email-contact%40fixteam.uk-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
    <a href="https://wa.me/5527988090038"><img src="https://img.shields.io/badge/WhatsApp-Atendimento-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"></a>
    <img src="https://img.shields.io/badge/Status-Disponível%20para%20Projetos-00e5ff?style=for-the-badge" alt="Status">
  </p>

  <p align="center">
    <i>Transformando desafios operacionais e regras de negócio complexas em ecossistemas digitais escaláveis, resilientes e de alta performance.</i>
  </p>

  <br/>

  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

</div>

<br/>

## 💡 Sobre Nós

A **FixTeam** é especializada em engenharia de software de ponta a ponta e desenvolvimento de soluções digitais de alto impacto. Atuamos desde a modelagem de backends de missão crítica, conciliação financeira e esteiras de inteligência artificial local até automações robóticas de alto volume (RPA) e interfaces web modernas de alta conversão.

Nossos projetos combinam **disciplina arquitetural**, **concorrência assíncrona**, **segurança multi-tenant** e **design refinado**, garantindo entregas robustas prontas para produção corporativa.

---

## 🎯 Pilares de Atuação

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ Engenharia de Backend & APIs</h3>
      <ul>
        <li><b>Arquitetura Hexagonal & Clean Architecture:</b> Isolamento rígido de domínios, Ports & Adapters e manutenibilidade.</li>
        <li><b>Isolamento Multi-Tenant:</b> Estratégia <i>Schema-per-Tenant</i> em PostgreSQL com controle granular de RBAC.</li>
        <li><b>Streaming & Mensageria:</b> Eventos em tempo real via <b>SSE (Server-Sent Events)</b>, WebSockets e Redis Pub/Sub.</li>
        <li><b>Conciliação & Ledgers:</b> Motores financeiros com idempotência, auto-balance e auditoria contínua.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🤖 RPAs Críticos & Web Scraping</h3>
      <ul>
        <li><b>Robôs de Alta Velocidade:</b> Disputa de pregões eletrônicos e cotações em tempo real com <b>HTTP/2</b> e <b>Playwright</b>.</li>
        <li><b>Automações Complexas:</b> Validação e preenchimento consular multi-etapas (DS-160) e bots corporativos.</li>
        <li><b>Bypass & Resiliência:</b> Tratamento adaptativo de rate limits, CAPTCHA v2/v3 e retries exponenciais com <i>Stamina</i>.</li>
        <li><b>Escalabilidade:</b> Orquestração de dezenas de instâncias simultâneas via <b>Celery</b> e <b>AsyncIO</b>.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 IA Aplicada, OCR & Extração</h3>
      <ul>
        <li><b>OCR Híbrido & Inteligente:</b> Processamento com <b>Docling (PyTorch)</b> local em CPU com fallback para IA em nuvem.</li>
        <li><b>Busca Semântica Local:</b> Inferência vetorial com <b>FastEmbed (ONNX)</b> direta no servidor sem custos abusivos de API.</li>
        <li><b>Regras De-Para & Classificação:</b> Triagem de extratos fiscais/bancários com categorização dinâmica e exportação ERP.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🌐 Plataformas Web & Landing Pages</h3>
      <ul>
        <li><b>Next.js, React & Tailwind CSS:</b> Interfaces ultra-rápidas, responsivas e otimizadas para SEO e conversão.</li>
        <li><b>Dashboards & Painéis em Tempo Real:</b> Visualização interativa de métricas, telemetria e conferência de dados.</li>
        <li><b>Design System Consistente:</b> Experiência de usuário premium com micro-animações e acessibilidade.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 📂 Nossos Projetos & Soluções em Destaque

<br/>

### 📊 **1. G2 Extratos Bancários — Suite de Extração & IA Contábil**
> **Solução corporativa para triagem, extração em lote e conciliação contábil automatizada.**
- **Pipeline em Lote:** Ingestão de pacotes ZIP e múltiplos PDFs de extratos bancários com processamento assíncrono.
- **Motor OCR Híbrido:** Extração de tabelas e textos via **Docling (PyTorch CPU)** não-bloqueante com controle de semáforos e fallback de LLM.
- **Conferência & De-Para:** Interface interativa de conferência lado a lado (Ctrl+Clique no PDF), drag-and-drop de lançamentos e exportação nativa para o sistema **Questor Contábil**.
- **Tecnologias:** `Python` · `Docling` · `FastAPI` · `Mistral AI` · `DuckDB` · `PostgreSQL`

---

### 🏛️ **2. Licitize — Plataforma de Disputa & Pregões Eletrônicos**
> **Plataforma corporativa de alto impacto para captura de editais e envio de lances em tempo real.**
- **Multi-Portais:** Integração e monitoramento contínuo em portais públicos (*ComprasGov*, *PNCP*, *BLL*, *BNC*, *LicitaNet*).
- **Disputa em Milissegundos:** Execução ultra-rápida via conexões HTTP/2 (`httpx`), retries com `Stamina` e bypass inteligente com `Playwright`.
- **Estratégias Adaptativas:** Modos de disputa automatizados (DE, PA, PAF), agendamento via `APScheduler` e resolução de desafios CAPTCHA.
- **Tecnologias:** `Python` · `Playwright` · `HTTP/2` · `FastAPI` · `Redis` · `Docker`

---

### 💳 **3. Ledger Financeiro & Contabilidade Multi-Tenant**
> **Backend white-label para registro contábil, liquidação fiat/crypto e conciliação de ledgers.**
- **Isolamento Total:** Arquitetura Hexagonal com *Schema-per-Tenant* (PostgreSQL 16) identificado dinamicamente por header `X-Tenant-ID`.
- **Tempo Real & Auditoria:** Transmissão de eventos de caixa via **SSE (Server-Sent Events)** com Redis Pub/Sub e auditoria detalhada via ELK Stack.
- **Qualidade Assegurada:** Cobertura abrangente com suíte de dezenas de testes automatizados (`Pytest`).
- **Tecnologias:** `Python (FastAPI)` · `SQLAlchemy 2.0 Async` · `PostgreSQL` · `Redis` · `Docker`

---

### 🚀 **4. FixTeam Projects & Plataformas Web (`new_project`)**
> **Novas plataformas digitais, dashboards analíticos e ecossistemas SaaS desenvolvidos pela FixTeam.**
- **Experiência Full Stack:** Backends modernos integrados a interfaces ricas, reativas e com telemetria ao vivo.
- **Alta Disponibilidade:** Ambientes conteinerizados com Docker, deploys automatizados via CI/CD e suporte a múltiplos bancos de dados.
- **Tecnologias:** `Next.js` · `React` · `Node.js` · `Fastify` · `Tailwind CSS` · `Prisma / SQLAlchemy`

---

## 🛠️ Stack Tecnológica & Ferramentas

<div align="center">

### 💻 Linguagens & Core
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

### ⚙️ Backend, APIs & Mensageria
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white" alt="Fastify" />
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma" />
  <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white" alt="Celery" />
</p>

### 🤖 IA, OCR & Automação (RPA)
<p>
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" alt="Playwright" />
  <img src="https://img.shields.io/badge/Docling_OCR-FF6F00?style=for-the-badge&logo=pytorch&logoColor=white" alt="Docling OCR" />
  <img src="https://img.shields.io/badge/FastEmbed_ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white" alt="FastEmbed" />
  <img src="https://img.shields.io/badge/Mistral_AI-F25C05?style=for-the-badge&logo=openai&logoColor=white" alt="Mistral AI" />
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium" />
  <img src="https://img.shields.io/badge/Puppeteer-40B5A4?style=for-the-badge&logo=puppeteer&logoColor=white" alt="Puppeteer" />
</p>

### 🗄️ Bancos de Dados & Armazenamento
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black" alt="DuckDB" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
</p>

### 🎨 Frontend & Interfaces Web
<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
</p>

### ☁️ DevOps, Nuvem & Qualidade
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Linux_/_Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Linux" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx" />
  <img src="https://img.shields.io/badge/Coolify-6B46C1?style=for-the-badge&logo=serverless&logoColor=white" alt="Coolify" />
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Pytest" />
</p>

</div>

---

## ⚙️ Padrões de Engenharia & Qualidade

```mermaid
flowchart LR
    A[Requisitos de Negócio] --> B[Arquitetura Hexagonal]
    B --> C[Domínio & Regras Limpas]
    C --> D[Testes Automatizados TDD]
    D --> E[Pipeline CI/CD & Docker]
    E --> F[Produção & Observabilidade]
```

- **🧪 Testes de Ponta a Ponta:** Cobertura de testes unitários e de integração para regras de negócio críticas.
- **🔒 Segurança & Isolamento:** Criptografia de ponta a ponta, autenticação segura (JWT, TOTP, RBAC) e isolamento estrito de dados.
- **📈 Observabilidade Ativa:** Monitoramento de logs, métricas de performance e alertas para garantir alta disponibilidade.
- **⚡ Entrega Contínua (CI/CD):** Pipelines automatizados para build, validação estática (`Ruff`, linters) e deploy sem downtime.

---

## 👤 Engenharia & Liderança Técnica

<div align="center">
  <br/>
  <a href="https://github.com/Isaac-Foster">
    <img src="https://avatars.githubusercontent.com/u/110870485?v=4" width="115px" style="border-radius: 50%; border: 3px solid #00e5ff; box-shadow: 0 4px 20px rgba(0, 229, 255, 0.3);" alt="Isack Vitor"/><br />
    <br/>
    <h3><b>Isack Vitor (@Isaac-Foster)</b></h3>
  </a>
  <p><b>Lead Backend Engineer · Arquiteto de Software · Engenheiro de RPAs & IA</b></p>
  <p><i>Especialista em microsserviços em Python, conciliação de ledgers financeiros, esteiras de OCR/IA local e automações de missão crítica.</i></p>

  <p>
    <a href="https://isaac-foster.github.io/"><img src="https://img.shields.io/badge/Portfólio_Oficial-000000?style=for-the-badge&logo=aboutdotme&logoColor=white" alt="Portfolio" /></a>
    &nbsp;
    <a href="https://github.com/Isaac-Foster"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
    &nbsp;
    <a href="https://linkedin.com/in/isack-foster"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    &nbsp;
    <a href="https://wa.me/5527988090038"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" /></a>
  </p>
  <br/>
</div>

---

## 🤝 Vamos Construir Algo Incrível Juntos?

Seja para automatizar processos críticos, criar motores de OCR e IA sob medida, integrar sistemas financeiros ou desenvolver plataformas web modernas e escaláveis, nossa equipe está pronta para atender seu projeto.

<div align="center">

  <br/>

  <a href="https://fixteam.uk" target="_blank">
    <img src="https://img.shields.io/badge/Website_Oficial-fixteam.uk-0070f3?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website" />
  </a>
  &nbsp;
  <a href="mailto:contact@fixteam.uk">
    <img src="https://img.shields.io/badge/Fale_Conosco-contact%40fixteam.uk-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  &nbsp;
  <a href="https://wa.me/5527988090038" target="_blank">
    <img src="https://img.shields.io/badge/WhatsApp-Iniciar_Conversa-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" />
  </a>

  <br/><br/>

  <p><sub>© 2026 <b>FixTeam</b> — Transformando ideias em soluções digitais de alto impacto.</sub></p>

</div>
