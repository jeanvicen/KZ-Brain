# ADR 0001 project structure — Estrutura modular do repositório

- **Status:** Accepted (direção documental; implementação não autorizada por este registro)
- **Data:** 2026-10-01

## Contexto
A visão inclui pesquisa, arquitetura e engenharia em domínios distintos; uma árvore plana dificulta ownership e evolução.

## Decisão
Adotar estrutura por domínio com documentação, arquitetura e espaços reservados separados. Manter `src/` sem código funcional nesta fase.

## Alternativas consideradas
Árvore plana ou estrutura orientada somente por linguagem. Ambas obscurecem as fronteiras conceituais.

## Consequências
Navegação mais clara; exige curadoria para evitar diretórios vazios e duplicação. Revisar quando os primeiros componentes forem aprovados.

## Revisão
Revisitar antes da primeira implementação, diante de novos requisitos, evidências de pesquisa ou risco material. Este ADR não declara que a capacidade está construída.
