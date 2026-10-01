# Integração futura: GitHub

> Sem OAuth, token, webhook, API call ou acesso automatizado implementado.

## Objetivo

Reservar um adaptador para operações autorizadas sobre repositórios e metadados, sem acoplar o núcleo a credenciais permanentes.

## Escopo e fronteira

Futuras capacidades podem incluir leitura de repositório, issues e pull requests. Escrita, merge, publicação e alteração de configurações devem ser permissões separadas, com confirmação e auditoria.

## Entradas / saídas

Entradas futuras: identidade, escopo aprovado, operação, recurso e limites. Saídas: dados com origem e timestamp, confirmação do provedor ou erro classificado.

## Riscos e evolução

Principais riscos: token com escopo amplo, prompt injection em conteúdo de repositório, vazamento de código privado, publicação acidental e rate limiting. Definir OAuth mínimo, armazenamento seguro, revogação, aprovação para side effects e redação de segredos antes de ativar.
