# ADR 0007 security boundaries — Segurança em fronteiras explícitas

- **Status:** Accepted (direção documental; implementação não autorizada por este registro)
- **Data:** 2026-10-01

## Contexto
Dados, ferramentas, conectores, modelos e artefatos atravessam limites de confiança diferentes.

## Decisão
Definir trust boundaries por componente, least privilege, revisão, isolamento e confirmação humana para efeitos relevantes.

## Alternativas consideradas
Uma política única implícita ou permissões amplas dentro do core.

## Consequências
Requer modelagem de ameaças contínua; controles reais ainda precisam ser desenhados e testados.

## Revisão
Revisitar antes da primeira implementação, diante de novos requisitos, evidências de pesquisa ou risco material. Este ADR não declara que a capacidade está construída.
