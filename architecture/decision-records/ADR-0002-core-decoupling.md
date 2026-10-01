# ADR 0002 core decoupling — Desacoplar o núcleo de provedores

- **Status:** Accepted (direção documental; implementação não autorizada por este registro)
- **Data:** 2026-10-01

## Contexto
Modelos, ferramentas e clientes podem evoluir separadamente e não devem dominar o domínio cognitivo.

## Decisão
Tratar contratos e adaptadores como fronteiras; o núcleo depende de capacidades abstratas e políticas, não de SDK de fornecedor.

## Alternativas consideradas
Acoplar diretamente o core a um modelo, ferramenta ou provedor único.

## Consequências
Mais abstrações a projetar, mas reduz dependência; validar com protótipo autorizado em fase futura.

## Revisão
Revisitar antes da primeira implementação, diante de novos requisitos, evidências de pesquisa ou risco material. Este ADR não declara que a capacidade está construída.
