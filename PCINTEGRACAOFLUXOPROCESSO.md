# 📊 Tabela: PCINTEGRACAOFLUXOPROCESSO

### Estrutura de Colunas e Restrições

                   Tabela            Coluna Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOFLUXOPROCESSO           IDFLUXO  NUMBER(5,0)                                        Id do fluxo;            OPERACIONAL                        NaN
PCINTEGRACAOFLUXOPROCESSO    CODIGOPROCESSO NUMBER(10,0)                                 Código do processo;            OPERACIONAL                        NaN
PCINTEGRACAOFLUXOPROCESSO                ID NUMBER(10,0)                          Identificação do registro;    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOFLUXOPROCESSO INTERVALOSEGUNDOS NUMBER(10,0) Intervalo de Tempo (em segundos) entre as Execuções            OPERACIONAL                        NaN
PCINTEGRACAOFLUXOPROCESSO         DESCRICAO VARCHAR2(80)                    Descrição do Processo em questão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*