![Caderno Blue Team — NotebookLM e aprendizagem ativa](docs/assets/caderno-blue-team-banner.png)

# Caderno Temático Blue Team

Caderno de segurança da informação que usa NotebookLM e IA como apoio à aprendizagem ativa, com foco em fundamentos defensivos, SOC, SIEM e resposta a incidentes.

![Blue Team](https://img.shields.io/badge/Blue_Team-learning-0EA5E9?style=flat-square) ![SOC](https://img.shields.io/badge/SOC-fundamentals-0F766E?style=flat-square) ![NotebookLM](https://img.shields.io/badge/NotebookLM-study-4285F4?style=flat-square) ![License](https://img.shields.io/badge/License-MIT-2EA44F?style=flat-square)

## Conteúdo

| Material | Finalidade |
|---|---|
| [Mini guia Blue Team](docs/mini-guia-blue-team.md) | Conceitos iniciais de CIA, defesa, SOC e SIEM |
| [Glossário](docs/glossario.md) | Termos essenciais para consulta rápida |
| [Roadmap](docs/roadmap-blue-team.md) | Trilha progressiva de fundamentos a resposta a incidentes |
| [Prompts reutilizáveis](prompts/prompts-blue-team.md) | Perguntas para explicar, comparar, revisar e praticar |
| [Fontes](sources/) | Notas de referência separadas por organização |

## Método de estudo

1. selecionar uma fonte e definir a pergunta de aprendizagem;
2. pedir uma explicação ancorada no material fornecido;
3. conferir a resposta na fonte original;
4. registrar resumo e termos no caderno;
5. criar questões de recuperação ativa;
6. revisar o roadmap e marcar somente o conteúdo realmente estudado.

## Estrutura

```text
docs/
├── assets/caderno-blue-team-banner.png
├── glossario.md
├── mini-guia-blue-team.md
└── roadmap-blue-team.md
prompts/
└── prompts-blue-team.md
sources/
├── cis-controls.md
├── ibm-incident-response.md
├── microsoft-learn.md
├── nist.md
└── owasp.md
```

## Limites

As notas são material de estudo e não substituem documentação oficial, treinamento prático, validação técnica ou procedimentos da organização. Respostas produzidas por IA devem ser conferidas antes de serem usadas em um contexto operacional.

## Privacidade

Não adicione logs reais, dados de incidentes, credenciais, nomes de clientes ou documentos internos. Use exemplos fictícios e sanitizados. Arquivos `.env`, bancos locais, exports e caches são ignorados pelo Git.

## Autor e licença

**Edmilson Gomes** — [GitHub @EDY075](https://github.com/EDY075)

Distribuído sob a [Licença MIT](LICENSE).
