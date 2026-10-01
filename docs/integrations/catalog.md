# Catálogo conceitual de conectores

> Este catálogo descreve áreas de pesquisa. Nenhum conector listado está ativo, autenticado ou autorizado a executar ações.

| Categoria | Uso futuro possível | Fronteira e controle mínimo |
|---|---|---|
| GitHub | Leitura de metadados, issues e repositórios; operações de escrita separadas | OAuth de escopo mínimo, confirmação para efeitos externos, isolamento de conteúdo não confiável |
| Hugging Face | Consultar metadados e avaliar artefatos/modelos | Revisar licença, proveniência, revisão/versão, checksums e código remoto antes de qualquer execução |
| Bancos de dados | Consultas a fontes autorizadas | Identidade por serviço, permissões por operação, consultas parametrizadas, minimização e trilha de auditoria |
| Storage | Armazenar ou recuperar artefatos e documentos | Classes de dados, criptografia, retenção, exclusão, ACLs e validação de conteúdo |
| Servidores MCP | Descoberta e chamada de capacidades padronizadas | Allowlist, identidade do servidor, schemas, versionamento, permissões por ferramenta e sandbox |
| APIs externas | Acesso a serviços web aprovados | Escopos mínimos, limites, validação de resposta, timeout, rate limit, provenance e revisão de termos |
| Serviços locais | Acesso limitado a recursos controlados pelo operador | Separação de rede, identidade, allowlist e proteção contra SSRF e escalada de privilégios |
| Ferramentas de desenvolvimento | Automação de tarefas técnicas aprovadas | Preferir leitura e dry-run; restringir shell/escrita; revisão humana para publicação, deploy ou exclusão |

## Ciclo conceitual

`registro → descoberta de capacidade → política/permissões → execução isolada → validação do resultado → observabilidade redigida`

Nenhuma descrição acima é uma instrução de conexão. Antes de implementar, cada integração exige análise de ameaça própria, finalidade, licenças/termos, plano de credenciais e critérios de revogação. Para MCP, consulte [a página de planejamento](mcp.md); para conectores concretos em estudo, consulte [GitHub](github.md) e [Hugging Face](hugging-face.md).
