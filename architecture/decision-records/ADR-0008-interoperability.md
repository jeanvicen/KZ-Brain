# ADR 0008 interoperability — Interoperabilidade através de adaptadores

- **Status:** Accepted (direção documental; implementação não autorizada por este registro)
- **Data:** 2026-10-01

## Contexto
Protocolos abertos podem facilitar conexão sem tornar o domínio dependente de um fornecedor.

## Decisão
Avaliar protocolos públicos como contratos na borda, isolados por adaptadores, permissões e verificação de versão.

## Alternativas consideradas
Acoplar domínio a um protocolo sem abstração ou rejeitar interoperabilidade sem avaliação.

## Consequências
Melhora substituibilidade, mas cria superfície adicional; cada adaptador requer threat model e compatibilidade.

## Revisão
Revisitar antes da primeira implementação, diante de novos requisitos, evidências de pesquisa ou risco material. Este ADR não declara que a capacidade está construída.
