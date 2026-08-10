# 📊 Tabela: PCINTEGRACAOGESTAOFLUXO

### Estrutura de Colunas e Restrições

                 Tabela         Coluna Tipo/Tamanho                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOGESTAOFLUXO             ID NUMBER(19,0)                                            Id do registro.    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOGESTAOFLUXO    DATAINICIAL TIMESTAMP(6)                       Data de início da execução do fluxo.            OPERACIONAL                        NaN
PCINTEGRACAOGESTAOFLUXO      DATAFINAL TIMESTAMP(6)                          Data de fim da execução do fluxo.            OPERACIONAL                        NaN
PCINTEGRACAOGESTAOFLUXO STATUSEXECUCAO  NUMBER(1,0)                               Status da execução do fluxo.            OPERACIONAL                        NaN
PCINTEGRACAOGESTAOFLUXO        IDFLUXO  NUMBER(5,0)                                               Id do fluxo.            OPERACIONAL                        NaN
PCINTEGRACAOGESTAOFLUXO   RECURSOFALHA VARCHAR2(60)   Em caso de falha, descreve o nome do recurso que falhou.            OPERACIONAL                        NaN
PCINTEGRACAOGESTAOFLUXO           ERRO         CLOB                     Em caso de falha, a descrição do erro.            OPERACIONAL                        NaN
PCINTEGRACAOGESTAOFLUXO       CONTADOR  NUMBER(5,0) Campo para controle das últimas X execuções de cada fluxo.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*