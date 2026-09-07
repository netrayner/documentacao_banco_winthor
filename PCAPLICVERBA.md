# 📊 Tabela: PCAPLICVERBA

### Estrutura de Colunas e Restrições

      Tabela         Coluna Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAPLICVERBA       NUMAPLIC  NUMBER(8,0)                                                NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCAPLICVERBA      CODFILIAL  VARCHAR2(2)                                                NaN            OPERACIONAL                        NaN
PCAPLICVERBA       NUMVERBA  NUMBER(8,0)                                                NaN            OPERACIONAL                        NaN
PCAPLICVERBA        DTAPLIC         DATE                                                NaN            OPERACIONAL                        NaN
PCAPLICVERBA       CODCONTA NUMBER(10,0)                                                NaN            OPERACIONAL                        NaN
PCAPLICVERBA        VLAPLIC NUMBER(14,6)                                                NaN            OPERACIONAL                        NaN
PCAPLICVERBA   REBAIXACUSTO  VARCHAR2(1)                                                NaN            OPERACIONAL                        NaN
PCAPLICVERBA           OBS1 VARCHAR2(40)                                                NaN            OPERACIONAL                        NaN
PCAPLICVERBA           OBS2 VARCHAR2(40)                                                NaN            OPERACIONAL                        NaN
PCAPLICVERBA CODFUNCREBAIXA  NUMBER(8,0)                                                NaN            OPERACIONAL                        NaN
PCAPLICVERBA CODFUNCESTORNO  NUMBER(8,0)                                                NaN            OPERACIONAL                        NaN
PCAPLICVERBA      DTESTORNO         DATE                                                NaN            OPERACIONAL                        NaN
PCAPLICVERBA     ROTINALANC  NUMBER(6,0)                     Indica a rotina de lançamento.            OPERACIONAL                        NaN
PCAPLICVERBA     DTCADASTRO         DATE                        Indica a data de casdastro.            OPERACIONAL                        NaN
PCAPLICVERBA    NUMTRANSENT NUMBER(10,0)                    Número de transação de entrada.            OPERACIONAL                        NaN
PCAPLICVERBA        NUMVIAS  NUMBER(2,0) Número de vias de impressao da aplicação de verba.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*