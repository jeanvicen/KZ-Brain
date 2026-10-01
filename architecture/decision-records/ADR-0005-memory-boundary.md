# ADR 0005 memory boundary — Isolar memória do contexto transitório

- **Status:** Accepted (direção documental; implementação não autorizada por este registro)
- **Data:** 2026-10-01

## Contexto
Contexto de tarefa e informação persistida têm semânticas, retenção e riscos de privacidade diferentes.

## Decisão
Separar working/session memory das categorias persistentes e exigir consentimento, isolamento, proveniência, expiração e exclusão para persistência futura.

## Alternativas consideradas
Tratar todo o contexto como memória permanente ou não distinguir classes.

## Consequências
Eleva transparência e controle, mas requer política e testes de isolamento antes de implementação.

## Revisão
Revisitar antes da primeira implementação, diante de novos requisitos, evidências de pesquisa ou risco material. Este ADR não declara que a capacidade está construída.
