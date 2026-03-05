# aios-god-mode-template

God Mode template for **Synkra AIOS** — complete agent personas, skills, rules and framework configuration.

## v4.0.0

- `aiox-god-mode` is now the **primary skill** with full God Mode functionality
- `aios-god-mode` is a **legacy redirect** that activates `aiox-god-mode` automatically
- Support for **6 AI Tools**: Claude Code, Codex, Gemini, Cursor, GitHub Copilot, Antigravity
- Codex support with `openai.yaml` and `AGENTS.md` skills list

## Usage

This template is used by [`create-aios-god-mode`](https://github.com/gutomec/create-aios-god-mode) and [`create-aiox-god-mode`](https://github.com/gutomec/create-aiox-god-mode) to install the God Mode skill into projects.

```bash
npx create-aios-god-mode my-project
# or
npx create-aiox-god-mode my-project
```

## Contents

- `template/skills/aiox-god-mode/` — Main God Mode skill (AIOX branding)
- `template/skills/aios-god-mode/` — Legacy redirect to `aiox-god-mode`
- `template/rules/` — Framework rules and agent authority
- `template/config/` — Framework configuration (settings.json, deny rules)

## Backward Compatibility

The `/aios-god-mode` slash command still works — it redirects to `/aiox-god-mode` seamlessly. No action needed from existing users.

## Credits

Based on [Synkra AIOS](https://github.com/SynkraAI/aios-core) by [Pedro Valério](https://github.com/Pedrovaleriolopez) / [SynkraAI](https://github.com/SynkraAI).

## License

MIT

> **Um prompt. Sistema completo. Zero trabalho manual.**
>
> Os exemplos abaixo mostram prompts do God Mode que produzem sistemas completos — landing page + painel admin + backend + imagens geradas por IA — tudo orquestrado por agentes AIOS. De briefings detalhados a instruções simples, os resultados são igualmente impressionantes.

<details>
<summary><strong>🏥 Exemplo Real: Clínica Médica Premium — Landing Page High-Ticket + Sistema Admin</strong></summary>

<br>

Copie este prompt no Claude Code após ativar `/aios-god-mode`:

---

### 🏥 CLÍNICA PREMIUM HIGH-TICKET MODE

Ative `aios-god-mode`.

Você irá **conceber, posicionar e implementar** uma landing page e sistema completo para uma clínica de nutrologia com posicionamento premium.

O objetivo NÃO é vender um plano de R$347.

O objetivo é vender:

> 🔥 Um programa médico exclusivo de transformação metabólica contínua
> (O valor é R$347/mês, mas a percepção deve ser de algo que valeria R$1.500+)

---

#### 🎯 POSICIONAMENTO ESTRATÉGICO

Antes de executar qualquer código:

**1️⃣ Defina o posicionamento**

A clínica não vende emagrecimento.
Ela vende:

* Longevidade
* Performance
* Controle metabólico
* Supervisão médica contínua
* Segurança clínica
* Método estruturado

Evite linguagem popular.
Use linguagem médica sofisticada e acessível.

---

**2️⃣ Defina o Avatar Premium**

Público-alvo:

* Homens e mulheres 30–55+
* Empresários
* Profissionais liberais
* Pessoas com rotina intensa
* Que já tentaram dietas
* Que valorizam acompanhamento médico real

Eles não querem "dieta".
Eles querem:

* Controle
* Segurança
* Acompanhamento
* Método científico
* Resultado previsível

---

#### 🧠 ESTRUTURA DA LANDING (HIGH-TICKET)

**HERO SECTION**

* Headline forte e elegante
* Subheadline médica e técnica
* CTA discreto e sofisticado
* Imagem premium estilo editorial médico

Exemplo de direção (não copie literalmente):

> "Supervisão Médica Contínua Para Transformação Metabólica Sustentável."

---

**SEÇÃO 1 — AUTORIDADE**

* Apresentação da equipe médica
* Formação, CRM, Especializações
* Método exclusivo

Tom: Confiança silenciosa. Sem exagero. Sem hype.

---

**SEÇÃO 2 — O MÉTODO**

Explicar o método como um protocolo estruturado:

* Avaliação metabólica
* Estratégia personalizada
* Monitoramento contínuo
* Ajustes clínicos
* Acompanhamento da equipe

Nomeie o método. Ex: *Protocolo de Regulação Metabólica Contínua™*

---

**SEÇÃO 3 — DIFERENCIAL**

Comparar implicitamente com dietas genéricas, apps, influenciadores, programas sem médico.
Sem atacar diretamente.

---

**SEÇÃO 4 — PROVA SOCIAL PREMIUM**

* Depoimentos elegantes
* Fotos discretas
* Histórias realistas
* Transformações sem exagero visual

Nada apelativo.

---

**SEÇÃO 5 — INVESTIMENTO**

Apresente como:

> Programa de Acompanhamento Médico Contínuo
> Investimento mensal: R$347

Ancoragem psicológica antes: consultas avulsas, nutricionistas, personal, exames, tempo perdido.

---

#### 📸 IMAGENS (nano banana pro)

Gerar imagens no padrão:

* Fotografia médica editorial
* Luz natural, ambiente clean
* Consultório sofisticado
* Expressões confiantes
* Pacientes reais (não fitness influencer)

Estilo: Tons neutros, branco, bege, azul clínico. Sem exagero de saturação. Sem aparência artificial.

---

#### 💾 BACKEND

**Banco SQLite:**

| Tabela | Campos |
|--------|--------|
| `leads` | id, nome, email, telefone, data_cadastro, origem, status, observacoes |
| `users` (admin) | id, nome, email, senha_hash, role, data_criacao |

---

#### 🔐 AUTENTICAÇÃO

* Login seguro com senha hash
* Proteção de rotas
* Sessão autenticada
* Logout

---

#### 📊 PAINEL ADMIN PREMIUM

Design limpo estilo SaaS médico.

**Dashboard:** Total de leads, leads por período, gráfico de crescimento, conversões, origem de tráfego.

**Tabela de leads:** Ordenação, filtro, busca, paginação + botão **Exportar para Excel (.xlsx)**.

---

#### 🎨 ESTILO VISUAL

* Minimalista, espaçamento generoso
* Tipografia elegante
* Animações sutis, transições suaves
* UX fluida

Referência mental: SaaS médico americano, clínica de luxo, estética discreta.

---

#### ⚙️ EXECUÇÃO

1. Planeje estrategicamente tudo
2. Defina arquitetura
3. Estruture código
4. Implemente frontend + backend
5. Gere imagens
6. Organize estrutura de pastas
7. Entregue pronto para deploy

Execute tudo usando `aios-god-mode`.

Nível exigido:

> Clínica de alto padrão.
> Produto que transmite confiança médica absoluta.
> Conversão elegante, não agressiva.

---

<br>

**O que o AIOS faz com esse prompt:**

| Agente | Ação |
|--------|------|
| `@architect` | Projeta a arquitetura full-stack (Next.js + SQLite + Auth) |
| `@ux-design-expert` | Cria spec de UI premium com estética editorial médica |
| `@dev` | Implementa landing page, painel admin e API backend |
| `@data-engineer` | Projeta schema SQLite com índices adequados |
| `@qa` | Valida qualidade, segurança e responsividade |
| `nano-banana-pro` | Gera fotografia médica editorial via MCP |
| `@devops` | Faz push para o GitHub quando pronto |

</details>

<br>

> [!TIP]
> **Você não precisa de um prompt detalhado para ter resultados impressionantes.** O exemplo abaixo é muito mais simples — e o God Mode entrega um sistema completo e pronto para produção com a mesma qualidade.

<details>
<summary><strong>⚡ Exemplo Rápido: Mesmo Projeto, Prompt Simples — Resultados Igualmente Impressionantes</strong></summary>

<br>

Este prompt mais curto alcança o mesmo escopo — landing page, backend, painel admin, fotos com IA, gestão de leads — com instruções mínimas. O God Mode preenche as lacunas usando suas skills e expertise de agentes integrados:

---

Ative sua skill aios-god-mode.

Utilize AIOS para criar uma landing page de alta conversão para um sistema de acompanhamento médico de uma clínica de nutrologia. A equipe médica deve estar disponível para acompanhamento contínuo de atendimentos relacionados à nutrologia, como emagrecimento e reeducação alimentar.

O plano de assinatura mensal custa R$347.

Gere fotografias utilizando nano banana pro com qualidade de fotógrafo profissional, transmitindo credibilidade, profissionalismo e padrão premium.

Implemente um sistema completo com backend que:

- Salve os leads em um banco de dados SQLite.
- Possua painel de administração com autenticação via SQLite.
- Permita que usuários cadastrados analisem estatísticas dos leads coletados.
- Exiba uma tabela com os leads cadastrados.
- Tenha um botão para exportação dos leads em formato Excel (.xlsx).

Para o planejamento do projeto, utilize suas melhores skills estratégicas. Após concluir o planejamento, execute toda a implementação utilizando a skill aios-god-mode.

---

<br>

**Mesmo resultado, menos esforço.** Os agentes do God Mode lidam autonomamente com tudo:

| O Que Você Escreveu | O Que o AIOS Faz |
|---------------------|-------------------|
| "landing page de alta conversão" | `@ux-design-expert` projeta layout otimizado para conversão, `@dev` implementa |
| "fotografias com nano banana pro" | Gera fotografia médica profissional via MCP |
| "leads em SQLite" | `@data-engineer` projeta o schema, `@dev` implementa a API CRUD |
| "painel de administração com autenticação" | Sistema completo de auth + dashboard admin com estatísticas |
| "exportação em Excel" | Exportação `.xlsx` usando a skill `xlsx` |
| "melhores skills estratégicas" | `@architect` planeja a arquitetura, `@pm` define requisitos |

> **A diferença?** O prompt detalhado dá controle preciso sobre posicionamento, tom de copy e direção visual. O prompt simples deixa o AIOS tomar essas decisões por você. Ambos entregam resultados prontos para produção.

</details>

---

## ✨ Funcionalidades

- **⚡ God Mode** — Orquestração completa com 10 personas de IA especializadas, cada uma com comandos dedicados
- **🤖 Sistema de Agentes** — Ative agentes com `@nome-do-agente`, execute comandos com `*comando`. Protocolo de handoff integrado preserva contexto entre trocas
- **📖 Desenvolvimento Orientado a Stories** — Todo trabalho flui por stories: `@sm *draft` → `@po *validate` → `@dev *develop` → `@qa *gate`
- **👥 Sistema de Squads** — Squads multi-agente pré-configurados para workflows de domínios específicos (dev de framework, design de marca, landing pages)
- **🧩 Ecossistema de Skills** — 22 skills da comunidade instaladas automaticamente: frontend, backend, SEO, pagamentos, documentos, geração com IA
- **🔌 Integração MCP** — 3 servidores MCP pré-configurados em `.mcp.json` para geração de imagens com IA, documentação ao vivo e componentes UI
- **🛡️ Proteção do Framework** — Modelo de 4 camadas com deny rules determinísticas em `settings.json`. Arquivos L1/L2 são imutáveis
- **🔄 QA Loop** — Ciclo automatizado de revisão-correção: `@qa review → veredito → @dev corrige → re-review` (máx. 5 iterações)
- **📋 Spec Pipeline** — Transforma requisitos informais em specs executáveis com seleção de fases baseada em complexidade (3-6 fases)
- **🔍 Brownfield Discovery** — Avaliação de débito técnico em 10 fases para codebases existentes com coleta de dados multi-agente

---

## 📦 Fluxo de Instalação

O instalador executa um **pipeline automatizado de 10 etapas**:

| Etapa | Descrição |
|:-----:|-----------|
| 1 | 🔍 **Validar ambiente** — Verifica versão do Node.js, nome do projeto, diretório e rede |
| 2 | 🏗️ **Inicializar framework AIOS** — Baixa e estrutura `.aios-core/` com constitution, tasks e workflows |
| 3 | ⚡ **Instalar God Mode** — Baixa personas de agentes, skills e rules do [aios-god-mode-template](https://github.com/gutomec/aios-god-mode-template) |
| 4 | 👥 **Instalar squads** — Baixa e configura os pacotes de squads selecionados |
| 5 | 🔌 **Configurar servidores MCP** — Configura `nano-banana-pro`, `context7`, `21st-dev` em `.mcp.json` |
| 6 | 🧩 **Instalar skills do ecossistema** — 22 skills de repos da comunidade via `npx skills add` |
| 7 | 🚀 **Instalar framework GSD** — [Get Shit Done](https://www.npmjs.com/package/get-shit-done-cc) para gestão de projetos |
| 8 | 📦 **Instalar dependências** — Executa `npm install` dentro de `.aios-core/` |
| 9 | 🗃️ **Inicializar git** — `git init` com commit inicial |
| 10 | ✅ **Pronto** — Projeto preparado para desenvolvimento orientado por agentes |

---

## 🛠️ Comandos

### `init` (padrão)

Cria um novo projeto AIOS do zero.

```bash
npx create-aios-god-mode meu-projeto
npx create-aios-god-mode meu-projeto --yes    # Aceitar todos os padrões
```

### `update`

Atualiza um projeto existente para a versão mais recente do template.

```bash
cd meu-projeto
npx create-aios-god-mode update
```

### `doctor`

Executa verificações de saúde em uma instalação AIOS existente.

```bash
cd meu-projeto
npx create-aios-god-mode doctor
```

### `add-squad`

Adiciona uma nova configuração de squad ao projeto.

```bash
cd meu-projeto
npx create-aios-god-mode add-squad backend
```

---

<details>
<summary><h2>🤖 Agentes de IA</h2></summary>

Todos os agentes são ativados com `@nome-do-agente` e suportam comandos via prefixo `*`.

| Agente | Persona | Função | Comandos Principais |
|--------|---------|--------|---------------------|
| `@dev` | **Dex** | Desenvolvedor Full Stack | `*develop`, `*build-autonomous`, `*run-tests`, `*self-critique` |
| `@qa` | **Quinn** | Arquiteto de Testes | `*review`, `*gate`, `*security-check`, `*test-design` |
| `@architect` | **Aria** | Arquiteto Técnico | `*design-system`, `*tech-selection`, `*api-design` |
| `@pm` | **Morgan** | Product Manager | `*create-prd`, `*create-epic`, `*execute-epic`, `*write-spec` |
| `@po` | **Pax** | Product Owner | `*validate-story-draft`, `*close-story`, `*backlog-review` |
| `@sm` | **River** | Scrum Master | `*draft`, `*story-checklist` |
| `@analyst` | **Atlas** | Analista de Negócios | `*research`, `*feasibility-study`, `*user-research` |
| `@data-engineer` | **Dara** | Especialista em Banco de Dados | Design DDL, políticas RLS, migrações, otimização de queries |
| `@ux-design-expert` | **Uma** | Designer UX/UI | Specs frontend, jornadas de usuário, design systems |
| `@devops` | **Gage** | Gerente de Repositório | `*push`, `*create-pr`, `*release`, `*add-mcp` |
| `@aios-master` | **Orion** | Orquestrador do Framework | `*create`, `*modify`, `*run-workflow`, `*correct-course` |

**Comandos universais** (disponíveis em todos os agentes): `*help`, `*guide`, `*session-info`, `*yolo`, `*exit`

</details>

---

<details>
<summary><h2>🧩 Skills do Ecossistema</h2></summary>

22 skills instaladas automaticamente, organizadas por categoria:

#### Design & Frontend

| Skill | Fonte |
|-------|-------|
| `ui-ux-pro-max` | nextlevelbuilder/ui-ux-pro-max-skill |
| `frontend-design` | anthropics/skills |
| `web-design-guidelines` | vercel-labs/agent-skills |
| `vercel-react-best-practices` | vercel-labs/agent-skills |
| `vercel-composition-patterns` | vercel-labs/agent-skills |

#### SEO & Marketing

| Skill | Fonte |
|-------|-------|
| `seo-audit` | coreyhaines31/marketingskills |
| `programmatic-seo` | coreyhaines31/marketingskills |
| `schema-markup` | coreyhaines31/marketingskills |

#### CI/CD & Deploy

| Skill | Fonte |
|-------|-------|
| `github-actions-templates` | wshobson/agents |
| `deployment-pipeline-design` | wshobson/agents |

#### Pagamentos

| Skill | Fonte |
|-------|-------|
| `stripe-integration` | wshobson/agents |

#### Backend & Clean Code

| Skill | Fonte |
|-------|-------|
| `nodejs-backend-patterns` | wshobson/agents |
| `api-design-principles` | wshobson/agents |
| `architecture-patterns` | wshobson/agents |
| `error-handling-patterns` | wshobson/agents |
| `clean-code` | ratacat/claude-skills |

#### Engenharia de Prompts

| Skill | Fonte |
|-------|-------|
| `prompt-engineering-patterns` | wshobson/agents |

#### Geração de Mídia com IA

| Skill | Fonte |
|-------|-------|
| `ai-video-generation` | inference-sh/skills |
| `ai-image-generation` | inference-sh/skills |

#### Processamento de Documentos

| Skill | Fonte |
|-------|-------|
| `pdf` | anthropics/skills |
| `docx` | anthropics/skills |
| `xlsx` | anthropics/skills |
| `pptx` | anthropics/skills |

</details>

---

## 🔌 Servidores MCP

Pré-configurados em `.mcp.json` e prontos para uso:

| Servidor | Pacote | Propósito |
|----------|--------|-----------|
| **nano-banana-pro** | `@rafarafarafa/nano-banana-pro-mcp` | Geração de imagens com IA via Gemini |
| **context7** | `@upstash/context7-mcp` | Consulta de documentação de bibliotecas ao vivo |
| **21st-dev** | `@21st-dev/magic` | Busca e geração de componentes UI |

> [!NOTE]
> O `nano-banana-pro` requer a variável de ambiente `GEMINI_API_KEY`. Adicione-a ao seu arquivo `.env`.

---

## 📁 Estrutura do Projeto

```
meu-projeto/
├── .claude/
│   ├── settings.json              # Permissões do Claude Code + deny rules
│   ├── rules/                     # Regras de workflow, exemplos de tools, autoridade de agentes
│   ├── skills/                    # God Mode + 22 skills do ecossistema
│   └── CLAUDE.md                  # Instruções do projeto para o Claude
├── .aios-core/
│   ├── constitution.md            # Princípios do framework (imutável)
│   ├── core/                      # Módulos core do framework
│   ├── development/
│   │   ├── tasks/                 # Definições de tasks executáveis
│   │   ├── templates/             # Templates de documentos e código
│   │   ├── checklists/            # Checklists de validação
│   │   └── workflows/             # Workflows multi-etapa
│   └── data/                      # Registro de tools, dados de configuração
├── .mcp.json                      # Configuração dos servidores MCP
├── docs/
│   ├── stories/                   # Stories de desenvolvimento
│   ├── prd/                       # Documentos de requisitos do produto
│   └── architecture/              # Documentação de arquitetura do sistema
├── squads/                        # Configurações de squads
├── packages/                      # Pacotes do projeto
├── tests/                         # Suítes de teste
├── package.json
└── README.md
```

---

## 👥 Squads

Disponíveis durante a configuração interativa (ou todos selecionados com `--yes`):

| Squad | Descrição | Padrão |
|-------|-----------|:------:|
| **AFS** — AIOS Forge Squad | Desenvolvimento e contribuição ao framework | ✅ |
| **NSC** — Nirvana Squad Creator | Criação e gerenciamento de novos squads | ✅ |
| **BrandCraft** | Identidade de marca e design system | — |
| **Ultimate LP** | Criação de landing pages com workflow multi-agente | — |

---

## ⚙️ Opções e Configuração

| Opção | Descrição |
|-------|-----------|
| `--yes` | Aceitar todos os padrões sem prompts interativos |

### Prompts Interativos

Ao executar sem `--yes`, o instalador pergunta:

| Prompt | Opções | Padrão |
|--------|--------|--------|
| **Nome do projeto** | Qualquer nome válido em kebab-case | — |
| **Tipo de projeto** | `Greenfield` / `Brownfield` | Greenfield |
| **Idioma** | `Português (PT-BR)` / `English` | PT-BR |
| **Squads** | Seleção múltipla dos squads disponíveis | AFS + NSC |

---

<details>
<summary><h2>🔄 Workflows</h2></summary>

### Story Development Cycle (SDC) — Principal

O workflow principal de desenvolvimento, usado para toda implementação de stories:

```
@sm *draft → @po *validate → @dev *develop → @qa *gate → @devops *push
```

| Fase | Agente | Tarefa |
|------|--------|--------|
| Criar | `@sm` | Rascunho da story a partir de epic/PRD |
| Validar | `@po` | Checklist de 10 pontos → GO / NO-GO |
| Implementar | `@dev` | Código, testes, autocrítica |
| QA Gate | `@qa` | 7 verificações de qualidade → PASS / FAIL |

### QA Loop — Revisão Iterativa

Ciclo automatizado de revisão-correção após o QA gate inicial:

```
@qa review → veredito → @dev corrige → re-review (máx. 5 iterações)
```

### Spec Pipeline — Pré-Implementação

Transforma requisitos informais em especificações executáveis:

| Complexidade | Fases | Fluxo |
|--------------|-------|-------|
| Simples (≤8) | 3 | coletar → spec → crítica |
| Padrão (9-15) | 6 | coletar → avaliar → pesquisar → spec → crítica → planejar |
| Complexo (≥16) | 6+ | Todas as fases + ciclo de revisão |

### Brownfield Discovery — Avaliação de Legado

Avaliação de débito técnico em 10 fases para codebases existentes com coleta de dados (arquitetura, banco de dados, frontend), revisão multi-agente e geração de relatório executivo.

</details>

---

## 📋 Requisitos

| Requisito | Versão | Obrigatório |
|-----------|--------|:-----------:|
| **Node.js** | ≥ 18.0.0 | ✅ |
| **Git** | Qualquer recente | ✅ |
| **GitHub CLI** (`gh`) | Qualquer recente | Recomendado |
| **Claude Code** | Mais recente | ✅ |

---

## 🔗 Links Relacionados

- [Synkra AIOS](https://github.com/SynkraAI/aios-core) — O framework de Sistema Orquestrado por IA, por [Pedro Valério](https://github.com/Pedrovaleriolopez)
- [squads.sh](https://squads.sh) — Gerenciamento de squads para projetos AIOS
- [aios-god-mode-template](https://github.com/gutomec/aios-god-mode-template) — O template que este CLI utiliza
- [Get Shit Done](https://www.npmjs.com/package/get-shit-done-cc) — Framework de gestão de projetos

---

## 📄 Licença

[MIT](LICENSE) © [gutomec](https://github.com/gutomec)
