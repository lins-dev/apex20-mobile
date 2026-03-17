# apex20-mobile

App mobile do **Apex20** — Virtual Tabletop para RPG.

Será construído com React Native (Expo) e NativeWind. Permite controle remoto de ficha de personagem via WebSocket e visualização de grid em Realidade Aumentada (WebXR).

## Pré-requisitos

- Node.js v20+
- npm v10+
- Expo CLI

## Instalação

```bash
npm install
```

## Comandos

```bash
npm run lint       # ESLint
npm run typecheck  # verificação de tipos TypeScript
```

> O projeto Expo ainda não foi inicializado. Os comandos `dev`, `build` e `start` serão adicionados nessa etapa.

## Estrutura planejada

```
src/
  modules/     Funcionalidades isoladas por domínio (ADR-036)
  components/  Componentes globais
  hooks/       Hooks de infraestrutura
  lib/         Configurações de terceiros
```

## Documentação

Consulte o repositório [apex20-docs](https://github.com/lins-dev/apex20-docs).
