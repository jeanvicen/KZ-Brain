# Política conceitual de memória

> Reserva de arquitetura; nenhuma memória é persistida por este repositório.

## Domínios previstos

| Domínio | Escopo conceitual | Retenção a decidir |
|---|---|---|
| Working Memory | Estado temporário de uma operação | Somente durante o ciclo de tarefa |
| Session Memory | Contexto de uma sessão | Política de sessão e expiração |
| Semantic Memory | Fatos ou preferências declarados | Consentimento, fonte, revisão e exclusão |
| Episodic Memory | Eventos e interações | Finalidade e prazo explícitos |
| Long-Term Memory | Dados autorizados retidos entre sessões | Opt-in e controles de ciclo de vida |
| Knowledge Memory | Conhecimento documentado ou indexado | Proveniência, licença e atualização |
| Tool Memory | Metadados de execução e resultados necessários | Minimização, segurança e TTL |
| User Context | Contexto contextualizado por usuário | Isolamento estrito e consentimento |

## Requisitos antes de qualquer persistência

- Delimitar finalidade e classes de dados permitidas.
- Obter consentimento futuro, revogável e específico.
- Isolar por identidade no servidor, testar separação e impedir fallback permissivo.
- Definir criptografia, acesso, versionamento, expiração, exportação e exclusão verificável.
- Rastrear origem e confiança; separar conteúdo externo não confiável de instruções de sistema.
- Documentar recuperação, ranking, correção e forma de exibir o uso da memória.
- Evitar gravar segredos, dados sensíveis ou informações de terceiros sem base apropriada.

## Aberturas

Como reconciliar exclusão com backups; como detectar memória incorreta; qual política de consentimento cabe a cada domínio; e quais dados jamais devem ser lembrados. Todas permanecem decisões pendentes.
