# O que é o FLOW Method?

Um módulo de desenvolvimento ágil orientado por IA com inteligência adaptativa — ajusta-se automaticamente desde correções simples até sistemas empresariais.

- **Adaptativo** — Ajusta a profundidade do planejamento com base na complexidade do projeto
- **Workflows Estruturados** — Baseado em boas práticas ágeis para análise, planejamento, arquitetura e implementação
- **Agentes Especializados** — 12+ especialistas de domínio (PM, Arquiteto, Desenvolvedor, UX, Scrum Master e mais)
- **Ciclo Completo** — Do brainstorming ao deployment

## Quick Start

**Pré-requisitos**: [Node.js](https://nodejs.org) v20+

```bash
npx @flownetbr/flow-method install
```

Siga os prompts do instalador e abra sua IDE com IA (Claude Code, Cursor etc.) na pasta do projeto.

## 🧭 Comandos

Após instalar, use os comandos abaixo na sua IDE com IA. Todos são invocados com `/` (ex.: `/flow-help`).

> ### ⭐ Nunca fique perdido
> Em qualquer momento do projeto, digite **`/flow-help`** seguido da sua dúvida.
> Ele analisa onde você está e diz exatamente qual é o próximo passo.
> Ex.: `/flow-help terminei a arquitetura, e agora?`

### 1️⃣ Primeiros passos

| Comando | Quando usar |
| --- | --- |
| `/flow-master` | 🧙 **Porta de entrada** — orquestrador geral: lista tasks (`LT`), lista workflows (`LW`) e executa qualquer etapa |
| `/flow-party-mode` | 🎉 Quer conversar com vários agentes ao mesmo tempo? |
| `/flow-bmm-set-feature` | 📁 Organiza os artefatos por feature antes de começar |

### 2️⃣ Qual caminho seguir?

| Você quer... | Trilha recomendada |
| --- | --- |
| 💡 Criar um produto novo do zero | `/flow-brainstorming` → `/flow-create-product-brief` → `/flow-create-prd` → `/flow-create-architecture` → `/flow-create-epics-and-stories` → `/flow-sprint-planning` |
| 🔧 Fazer uma mudança ou correção pequena | `/flow-quick-spec` → `/flow-quick-dev` |
| 📝 Implementar uma story já criada | `/flow-dev-story` |
| 🔍 Revisar algo que já foi feito | `/flow-code-review` · `/flow-review-adversarial-general` |
| ❓ Só entender como funciona | `/flow-help` |

### 3️⃣ Agentes especialistas

Cada comando ativa um agente com persona e menu interativo próprio:

| Comando | Agente | Papel |
| --- | --- | --- |
| `/flow-analyst` | 📊 Mary | Business Analyst — pesquisa e análise de negócio |
| `/flow-pm` | 📋 John | Product Manager — PRDs e requisitos |
| `/flow-architect` | 🏗️ Winston | Architect — arquitetura e decisões técnicas |
| `/flow-ux-designer` | 🎨 Sally | UX Designer — especificações de UX |
| `/flow-dev` | 💻 Amelia | Developer — implementação de stories |
| `/flow-sm` | 🏃 Bob | Scrum Master — stories e sprints |
| `/flow-qa` | 🧪 Quinn | QA Engineer — testes e qualidade |
| `/flow-tech-writer` | ✍️ Tech Writer | Documentação técnica |
| `/flow-quick-flow-solo-dev` | 🚀 Barry | Solo dev — fluxo rápido sem cerimônia |

### 4️⃣ Workflows completos por fase

<details>
<summary>📖 Ver todos os workflows</summary>

| Fase | Comandos |
| --- | --- |
| **Descoberta** | `/flow-brainstorming` · `/flow-create-product-brief` · `/flow-market-research` · `/flow-domain-research` · `/flow-technical-research` |
| **Planejamento** | `/flow-create-prd` · `/flow-edit-prd` · `/flow-validate-prd` · `/flow-create-ux-design` · `/flow-create-architecture` |
| **Epics & Sprints** | `/flow-create-epics-and-stories` · `/flow-check-implementation-readiness` · `/flow-sprint-planning` · `/flow-sprint-status` · `/flow-correct-course` |
| **Execução** | `/flow-create-story` · `/flow-dev-story` · `/flow-code-review` · `/flow-retrospective` · `/flow-qa-generate-e2e-tests` |
| **Contexto do projeto** | `/flow-generate-project-context` · `/flow-document-project` · `/flow-index-docs` · `/flow-shard-doc` · `/flow-bmm-set-feature` |

</details>

> 💡 **Regra prática:** projeto grande → siga a trilha completa da fase 2. Mudança pequena → atalho rápido. Dúvida em qualquer ponto → `/flow-help`.

## Documentação

- [Documentação do BMad Method (upstream)](https://docs.bmad-method.org) — Tutoriais, guias, conceitos e referência

# Fork
**Fork do [EVO Method](https://github.com/evolution-foundation/EVO-METHOD)** — que por sua vez é um fork do [BMad Method](https://github.com/bmad-code-org/BMAD-METHOD). Adaptado e mantido de forma independente.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Node.js Version](https://img.shields.io/badge/node-%3E%3D20.0.0-brightgreen)](https://nodejs.org)

**FLOW Method** é um framework de desenvolvimento ágil orientado por IA, derivado do [EVO Method](https://github.com/evolution-foundation/EVO-METHOD), que tem como base o [BMad Method](https://github.com/bmad-code-org/BMAD-METHOD). Este projeto evolui de forma independente, com adaptações e melhorias próprias.

## Origem

Este projeto é um fork do **EVO Method**, que por sua vez deriva do **BMad Method** (Build More, Architect Dreams), criado por Brian (BMad) Madison e mantido pela comunidade BMad. Agradecemos aos projetos anteriores e a todos os seus contribuidores.

Cadeia de proveniência:

| Projeto         | Repositório                                                                                              | Papel                          |
| --------------- | -------------------------------------------------------------------------------------------------------- | ------------------------------ |
| **BMad Method** | [bmad-code-org/BMAD-METHOD](https://github.com/bmad-code-org/BMAD-METHOD)                                 | Projeto original               |
| **EVO Method**  | [evolution-foundation/EVO-METHOD](https://github.com/evolution-foundation/EVO-METHOD)                     | Fork intermediário             |
| **FLOW Method** | este repositório                                                                                         | Fork atual (@SylvioNetoRj)     |

- **Documentação original:** [docs.bmad-method.org](https://docs.bmad-method.org)
- **Modificações deste fork:** descritas no [CHANGELOG.md](CHANGELOG.md)
- **Avisos de copyright preservados:** veja [LICENSE](LICENSE) e [CONTRIBUTORS.md](CONTRIBUTORS.md)




## Contribuindo

Contribuições são bem-vindas! Veja [CONTRIBUTING.md](CONTRIBUTING.md) para diretrizes.

## Licença

MIT License — veja [LICENSE](LICENSE) para detalhes.

---

**Nota:** Este é um fork independente. "BMad" e "BMad Method" são marcas da BMad Code, LLC; "EVO" e "EVO Method" são marcas da EVO Code, LLC. Essas marcas não são licenciadas sob a MIT License. Veja [TRADEMARK.md](TRADEMARK.md) para detalhes.
