# Contribuir

KZ-Brain está na **Foundation / Architecture Stage**. Contribuições devem fortalecer a clareza da arquitetura, pesquisa, documentação e segurança sem sugerir que funcionalidades futuras já existem.

## Antes de propor

- Leia [PRINCIPLES.md](PRINCIPLES.md), [ARCHITECTURE.md](ARCHITECTURE.md) e [SECURITY.md](SECURITY.md).
- Abra issue usando o template apropriado para bug documental, funcionalidade futura, pesquisa ou arquitetura.
- Para fontes externas, registre URL oficial, autoria/organização, finalidade, licença quando aplicável e data de consulta.

## Pull requests

- Descreva motivação, escopo, alternativas e riscos.
- Declare explicitamente se a mudança é documentação, configuração, asset ou código.
- Nesta fase, `src/` aceita somente documentação de placeholder. Não adicione runtime, treinamento, inferência, banco, API, agentes ou chamadas a provedores.
- Não adicione segredos, dados pessoais, datasets ou checkpoints.
- Confira links internos, diagramas Mermaid e status declarado.

## Processo

1. Discussão e escopo.
2. Revisão de arquitetura, privacidade e segurança.
3. Aprovação e registro em ADR quando a mudança altera uma fronteira.
4. Merge após revisão; nenhuma aprovação implícita de implementação futura.

As decisões de aceitação permanecem com os mantenedores do repositório.
