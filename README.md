# Claude Opus 4.8 — Relatório de Lançamento

Relatório de pesquisa sobre o lançamento do **Claude Opus 4.8** (Anthropic), publicado via GitHub Pages.

🔗 **Página:** https://inematds.github.io/opus48/

## Resumo

A Anthropic lançou o **Claude Opus 4.8** (`claude-opus-4-8`) em **28/05/2026**, ~42 dias após o Opus 4.7 — o ciclo mais rápido da família 4.x. Modelo de raciocínio híbrido com **1M de tokens** de contexto (200k no Foundry), 128k de saída e pensamento adaptativo, focado em codificação agêntica de longo horizonte.

| | |
|---|---|
| **Lançamento** | 28/05/2026 (quinta-feira) |
| **API ID** | `claude-opus-4-8` |
| **Contexto / saída** | 1M tokens (200k Foundry) / 128k |
| **Preço regular** | US$ 5/M entrada · US$ 25/M saída (inalterado vs 4.7) |
| **Fast mode** | 2,5× mais rápido · ~3× mais barato que o do 4.7 (US$ 10/US$ 50) |
| **Disponibilidade** | claude.ai, API, Bedrock, Vertex AI, Foundry, GitHub Copilot |

### Benchmarks (auto-reportados pela Anthropic)

- **SWE-bench Pro:** 69,2% (4.7: 64,3% · GPT-5.5: 58,6% · Gemini 3.1 Pro: 54,2%)
- **SWE-bench Verified:** 88,6%
- **OSWorld (uso de computador):** 83,4% · **Online-Mind2Web:** 84%
- **USAMO:** 96,7% · **HLE c/ ferramentas:** 57,9% · **AA Index:** 61,4

### Novidades

- Controle de esforço no claude.ai (Low/Medium/High/Extra/Max)
- Dynamic Workflows em research preview (centenas de subagentes paralelos no Claude Code)
- Fast mode ~3× mais barato; API Messages aceita `system` inline

## Metodologia

Pesquisa multi-fonte com verificação adversarial: 5 ângulos de busca · 20 fontes · 100 alegações extraídas · 25 verificadas por votação 3-vias → **25 confirmadas, 0 refutadas**.

> **Ressalva:** benchmarks são auto-reportados pela Anthropic, sem auditoria independente em escala. Relatório produzido em 30/05/2026 (cobertura de lançamento). Fontes e ressalvas completas na [página](https://inematds.github.io/opus48/).
