# ADR 0004 tool boundary — Controlar ferramentas por permissões e validação

- **Status:** Accepted (direção documental; implementação não autorizada por este registro)
- **Data:** 2026-10-01

## Contexto
Ferramentas podem causar efeitos externos e trazer conteúdo não confiável.

## Decisão
Usar registry conceptual, discovery, policy/permission gate, execução isolada, validação e observabilidade; ações sensíveis exigem aprovação humana.

## Alternativas consideradas
Executar chamada direta indicada pelo modelo sem validação.

## Consequências
Adiciona latência e desenho de política; reduz risco de ações invisíveis. Não há execução nesta fase.

## Revisão
Revisitar antes da primeira implementação, diante de novos requisitos, evidências de pesquisa ou risco material. Este ADR não declara que a capacidade está construída.
