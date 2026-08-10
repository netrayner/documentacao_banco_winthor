# 📊 Tabela: PCVERSAOOBJBD

### Estrutura de Colunas e Restrições

       Tabela               Coluna   Tipo/Tamanho                                                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVERSAOOBJBD           NOMEOBJETO   VARCHAR2(50)                                                               Nome do objeto no banco de dados.    CHAVE PRIMÁRIA (PK)                        NaN
PCVERSAOOBJBD             VERSAOPC   NUMBER(10,0)                                               Versão da rotina de atualização de objetos atual.            OPERACIONAL                        NaN
PCVERSAOOBJBD        VERSAOCLIENTE   NUMBER(10,0)                                          Versão da rotina de atualização de objetos no cliente.            OPERACIONAL                        NaN
PCVERSAOOBJBD           VALIDAROBJ    VARCHAR2(1)                                              Validar versionamento de objeto do banco de dados.            OPERACIONAL                        NaN
PCVERSAOOBJBD            MSGALERTA VARCHAR2(2000)                                Mensagem de alerta para atualização do objeto no banco de dados.            OPERACIONAL                        NaN
PCVERSAOOBJBD      DTATUALIZACAOPC           DATE                                                 Data da atualização do registro feito pela 560.            OPERACIONAL                        NaN
PCVERSAOOBJBD DTATUALIZACAOCLIENTE           DATE Data da atualização do registro feito pelas rotinas de atualização de objeto no banco de dados.            OPERACIONAL                        NaN
PCVERSAOOBJBD VALIDACAOOBRIGATORIA    VARCHAR2(1)              Define se a validação de versionamento de objetos do banco de dados é obrigatoria.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*