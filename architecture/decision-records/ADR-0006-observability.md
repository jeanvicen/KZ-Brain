# ADR 0006 observability — Observabilidade com minimização de dados

- **Status:** Accepted (direção documental; implementação não autorizada por este registro)
- **Data:** 2026-10-01

## Contexto
Depuração e resposta a incidentes futuras exigirão sinais, mas prompts e conteúdo podem ser sensíveis.

## Decisão
Planejar logs, métricas, traces e auditoria redigidos, com controle de acesso e retenção por classe.

## Alternativas consideradas
Registrar payloads completos ou operar sem trilhas.

## Consequências
A minimização reduz risco, com trade-off de diagnóstico; validar redaction e retenção antes de habilitar coleta.

## Revisão
Revisitar antes da primeira implementação, diante de novos requisitos, evidências de pesquisa ou risco material. Este ADR não declara que a capacidade está construída.
