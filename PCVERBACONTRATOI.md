# 📊 Tabela: PCVERBACONTRATOI

### Estrutura de Colunas e Restrições

          Tabela           Coluna Tipo/Tamanho                                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVERBACONTRATOI      NUMCONTRATO NUMBER(12,0)                                                                     Número do contrato.    CHAVE PRIMÁRIA (PK)           PCVERBACONTRATOC
PCVERBACONTRATOI          CODPROD  NUMBER(6,0)                                                                      Código do produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCVERBACONTRATOI CALCVLSEMIMPOSTO  VARCHAR2(1)                         Para calcular o produto utilizando ou não o valor dos impostos.            OPERACIONAL                        NaN
PCVERBACONTRATOI       TIPOINDICE  VARCHAR2(1)                                    Tipo do índice: Calculo por Percentual ou por valor.            OPERACIONAL                        NaN
PCVERBACONTRATOI         VLINDICE NUMBER(18,6) Valor do índice (podendo ser percentual ou valor, de acordo com a opção marcada acima).            OPERACIONAL                        NaN
PCVERBACONTRATOI       DTINCLUSAO         DATE                                                Data de inclusão do contrato no sistema.            OPERACIONAL                        NaN
PCVERBACONTRATOI       DTEXCLUSAO         DATE                                                              Data exclusão do contrato.            OPERACIONAL                        NaN
PCVERBACONTRATOI      DTALTERACAO         DATE                                                             Data alteração do contrato.            OPERACIONAL                        NaN
PCVERBACONTRATOI    CODUSUARIOINC  NUMBER(6,0)                                               Código do usuário que incluiu o contrato.            OPERACIONAL                        NaN
PCVERBACONTRATOI    CODUSUARIOEXC  NUMBER(6,0)                                               Código do usuário que excluiu o contrato.            OPERACIONAL                        NaN
PCVERBACONTRATOI    CODUSUARIOALT  NUMBER(6,0)                                               Código do usuário que alterou o contrato.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*