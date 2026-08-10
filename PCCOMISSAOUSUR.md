# 📊 Tabela: PCCOMISSAOUSUR

### Estrutura de Colunas e Restrições

        Tabela       Coluna Tipo/Tamanho                                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMISSAOUSUR      CODUSUR  NUMBER(4,0)                                                                                    NaN            OPERACIONAL                        NaN
PCCOMISSAOUSUR  PERCDESCINI NUMBER(18,6)                                                                                    NaN            OPERACIONAL                        NaN
PCCOMISSAOUSUR  PERCDESCFIM NUMBER(18,6)                                                                                    NaN            OPERACIONAL                        NaN
PCCOMISSAOUSUR       PERCOM  NUMBER(8,4)                                                                                    NaN            OPERACIONAL                        NaN
PCCOMISSAOUSUR     CODFAIXA  NUMBER(8,0)                                                                                    NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSAOUSUR TIPOCOMISSAO  VARCHAR2(1)                               Indica o tipo da comissão: D de Desconto ou V de Valor.             OPERACIONAL                        NaN
PCCOMISSAOUSUR         TIPO  VARCHAR2(2) Indica o tipo da comissão por RCA: R-RCA, RD-RCA/Depto, RS-RCA/Seção, RP-RCA/Produto.             OPERACIONAL                        NaN
PCCOMISSAOUSUR      CODEPTO  NUMBER(6,0)                                                      Indica o código do departamento.             OPERACIONAL                        NaN
PCCOMISSAOUSUR       CODSEC  NUMBER(6,0)                                                             Indica o código da seção.             OPERACIONAL                        NaN
PCCOMISSAOUSUR      CODPROD  NUMBER(6,0)                                                           Indica o código do produto.             OPERACIONAL                        NaN
PCCOMISSAOUSUR   DTMXSALTER         DATE                                                                                    NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*