# ai-common-docs

Repositório centralizador de conteúdos de IA para diversas ferramentas, como **GitHub Copilot**, **Claude Code**, **ChatGPT**, entre outras.

A ideia é manter em um único lugar todos os artefatos reutilizáveis — agentes, instruções, prompts e skills — organizados por ferramenta em suas respectivas pastas padrão.

---

## Estrutura de pastas

```
ai-common-docs/
│
├── .github/                   # Conteúdos para o GitHub Copilot (e ferramentas integradas ao GitHub)
│   ├── agents/                # Definições de agentes customizados
│   ├── instructions/          # Instruções customizadas (custom instructions)
│   ├── prompts/               # Templates de prompts reutilizáveis
│   └── skills/                # Definições de skills
│
├── .claude/                   # Conteúdos para o Claude Code (Anthropic)
│   ├── agents/                # Definições de agentes customizados
│   ├── instructions/          # Instruções customizadas
│   ├── prompts/               # Templates de prompts reutilizáveis
│   └── skills/                # Definições de skills
│
└── README.md                  # Este arquivo
```

> Novas ferramentas de IA podem ser adicionadas seguindo o mesmo padrão: uma pasta raiz dedicada à ferramenta contendo as subpastas `agents/`, `instructions/`, `prompts/` e `skills/`.

---

## Descrição das subpastas

| Subpasta | Descrição |
|---|---|
| `agents/` | Definições de agentes de IA configurados para tarefas específicas |
| `instructions/` | Instruções customizadas que orientam o comportamento da ferramenta |
| `prompts/` | Templates de prompts prontos para reuso em diferentes contextos |
| `skills/` | Habilidades ou capacidades adicionais que estendem a ferramenta |
