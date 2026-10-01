# ADR 0003 model runtime separation — Separar arquitetura do modelo, runtime e serving

- **Status:** Accepted (direção documental; implementação não autorizada por este registro)
- **Data:** 2026-10-01

## Contexto
Artefatos, algoritmos de modelo, execução e exposição de serviço têm ciclos de vida e ameaças diferentes.

## Decisão
Documentar model architecture, runtime, serving, registry e artifacts como responsabilidades separadas.

## Alternativas consideradas
Um pacote/serviço único cobrindo definição, pesos e serving.

## Consequências
Facilita substituição e governança de artefatos; requer metadados e compatibilidade explícitos.

## Revisão
Revisitar antes da primeira implementação, diante de novos requisitos, evidências de pesquisa ou risco material. Este ADR não declara que a capacidade está construída.
