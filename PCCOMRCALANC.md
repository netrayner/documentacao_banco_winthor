# 📊 Tabela: PCCOMRCALANC

### Estrutura de Colunas e Restrições

      Tabela     Coluna  Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMRCALANC     NUMSEQ  NUMBER(18,0)                          Vínculo com PCCOMRCA            OPERACIONAL                        NaN
PCCOMRCALANC     RECNUM   NUMBER(8,0)                            Vínculo com PCLANC            OPERACIONAL                        NaN
PCCOMRCALANC       TIPO   VARCHAR2(1) P - Pagamento, I - Imposto, C - Contrapartida            OPERACIONAL                        NaN
PCCOMRCALANC OBSERVACAO VARCHAR2(100)                                    Observação            OPERACIONAL                        NaN
PCCOMRCALANC     DTLANC          DATE                               Data Lançamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*