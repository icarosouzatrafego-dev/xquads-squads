# Xquads Squads

**As maiores mentes trabalhando para voce.**

13 squads de agentes IA especializados com workflows, tasks e configuracoes prontos para uso no Synkra AIOX.

## Squads Disponiveis

| Squad | Agentes | Foco |
|-------|---------|------|
| Advisory Board | 11 | Conselheiros estrategicos (Ray Dalio, Charlie Munger, Naval Ravikant...) |
| Brand Squad | 15 | Branding e posicionamento (David Aaker, Marty Neumeier, Al Ries...) |
| C-Level Squad | 6 | Lideranca executiva (CEO, CTO, CMO, COO, CIO, CAIO) |
| Claude Code Mastery | 8 | Dominio do Claude Code e AIOX |
| Copy Master | 33 | Copywriting avancado — mestres lendarios em profundidade |
| Copy Squad | 23 | Copywriting (Gary Halbert, Eugene Schwartz, David Ogilvy...) |
| Cybersecurity | 15 | Seguranca ofensiva e defensiva |
| Data Squad | 7 | Analytics, growth e comunidade (Sean Ellis, Avinash Kaushik...) |
| Design Squad | 8 | UX/UI e design systems (Brad Frost, Dan Mall...) |
| Hormozi Squad | 16 | Negocios e escala (framework Alex Hormozi) |
| Movement | 7 | Construcao de movimentos e comunidades |
| Storytelling | 12 | Narrativa e storytelling (Joseph Campbell, Oren Klaff...) |
| Traffic Masters | 16 | Trafego pago e midia (Pedro Sobral, Kasim Aslam...) |

## Como Instalar

### Opcao 1: Clonar este repositorio

```bash
git clone https://github.com/icarosouzatrafego-dev/xquads-squads.git
```

Copie a pasta para dentro do seu projeto aiox-core:

```bash
cp -r xquads-squads/* seu-projeto/squads/
```

### Opcao 2: Baixar o ZIP

Acesse [xquads.vercel.app/xquads/downloads](https://xquads.vercel.app/xquads/downloads) e baixe o pacote completo.

### Opcao 3: Instalar via AIOX Core

```bash
git clone https://github.com/SynkraAI/aiox-core.git
cd aiox-core
npm install
```

Depois siga as instrucoes de instalacao do proprio [aiox-core](https://github.com/SynkraAI/aiox-core).

## Estrutura de Cada Squad

```
squad-name/
├── squad.yaml          # Manifesto do squad (agentes, tasks, workflows)
├── agents/             # Definicoes de agentes (persona, role, focus, greeting)
├── tasks/              # Tasks executaveis com inputs/outputs
├── workflows/          # Workflows multi-agente automatizados
├── checklists/         # Checklists de qualidade
├── config/             # Configuracoes do squad
└── data/               # Frameworks e catalogos de referencia
```

## Pre-requisitos

- [Synkra AIOX Core](https://github.com/SynkraAI/aiox-core)
- Node.js 18+
- Claude Code (Anthropic CLI)

## Dashboard

Veja todos os agentes, bios e especialidades em: [xquads.vercel.app/xquads](https://xquads.vercel.app/xquads)

---

**Xquads by Synkra**
