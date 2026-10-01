# Arquitetura do KZ-Brain

> **Estado:** arquitetura conceitual. Nenhum componente descrito está implementado.

## Objetivo

Estabelecer fronteiras modulares para uma futura infraestrutura de IA sem acoplar o núcleo cognitivo a um modelo, fornecedor, transporte, ferramenta ou aplicação cliente.

## Camadas conceituais

1. **Percepção e representação:** receber modalidades futuras e convertê-las em representações contextualizadas.
2. **Contexto e memória:** compor contexto de tarefa com isolamento, retenção e consentimento definidos.
3. **Cognição:** raciocínio, planejamento e políticas de decisão, como capacidades futuras sujeitas a avaliação.
4. **Orquestração:** coordenar capacidades com limites, permissões, cancelamento e aprovação humana.
5. **Tools, especialistas e conectores:** fronteiras explícitas entre intenção, autorização, execução e validação.
6. **Model layer:** abstrair arquitetura, registro de modelos, artefatos e runtime sem presumir um fornecedor.
7. **Serving e clientes:** futura camada de implantação e contratos externos versionados.
8. **Fundação transversal:** segurança, observabilidade, avaliação, governança e interoperabilidade.

## Regras de dependência

- Camadas superiores dependem de contratos, não de detalhes internos dos provedores.
- O runtime não define a arquitetura do modelo; serving não é o registry; artefatos não são código executável confiável por padrão.
- Ferramentas e conectores operam somente sob uma fronteira de permissão e validação.
- Memória é um domínio separado do contexto transitório e exige política explícita de dados.
- API, SDK e aplicações cliente não acessam diretamente armazenamento interno privilegiado.

## Diagramas

Veja [diagrama de sistema](architecture/diagrams/system-overview.mmd), [mapa de diagramas](architecture/diagrams/README.md) e a [visão geral](docs/architecture/system/overview.md).

## Decisões

ADRs iniciais registram fronteiras propostas e são revisáveis antes da implementação. Eles não autorizam código, infraestrutura ou escolhas de fornecedores.
