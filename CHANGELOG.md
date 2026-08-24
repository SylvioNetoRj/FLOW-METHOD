# Changelog

> FLOW Method é um fork do [EVO Method](https://github.com/evolution-foundation/EVO-METHOD), que por sua vez deriva do [BMad Method](https://github.com/bmad-code-org/BMAD-METHOD), com melhorias, extensões e adaptações feitas pela equipe da Flownet. As versões abaixo refletem mudanças realizadas a partir da base herdada (BMad 6.0.4, via EVO).

---

## [1.0.6] - 2026-03-09

### 🎁 Features

* Atualiza mensagem de início da instalação para o lançamento do FLOW Method V6

---

## [1.0.5] - 2026-03-09

### 🎁 Features

* Adiciona skill `set-feature` para definir e alternar o contexto de feature ativa, organizando artefatos em subpastas por feature

---

## [1.0.4] - 2026-03-09

### 🎁 Features

* Adiciona skills nativas do Claude Code para os agentes FLOW instalados

---

## [1.0.3] - 2026-03-09

### ♻️ Refactoring

* Workflows passam a escrever conteúdo diretamente no arquivo de saída ao invés de apresentar ao usuário
* Padrão de menu de colaboração atualizado de A/P/C para A/P/C/R (adiciona opção Rewrite)

---

## [1.0.2] - 2026-03-09

### 🎁 Features

* Refatora workflows para suportar contexto de feature ativa (`active_feature`) com organização de artefatos em subpastas
* Adiciona diretiva de conciseness nos workflows `dev-story` e `quick-dev`

### ♻️ Refactoring

* Escopo do pacote npm atualizado para `@flownetbr/flow-method`

---

## [1.0.0] - 2026-03-09

### 🎁 Features

* Fork da base BMad Method 6.0.4 (via EVO Method) — rebrand completo para **FLOW Method**
* Atualização de repositório, autor e referências para Flownet
* Versão inicial publicada como `@flownetbr/flow-method`
