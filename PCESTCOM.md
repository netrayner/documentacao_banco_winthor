# 📊 Tabela: PCESTCOM

### Estrutura de Colunas e Restrições

  Tabela          Coluna Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTCOM     NUMTRANSENT NUMBER(10,0)                                                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCESTCOM     VLDEVOLUCAO NUMBER(14,2)                                                 NaN            OPERACIONAL                        NaN
PCESTCOM       VLESTORNO NUMBER(14,2)                                                 NaN            OPERACIONAL                        NaN
PCESTCOM       DTESTORNO         DATE                                                 NaN            OPERACIONAL                        NaN
PCESTCOM         CODUSUR  NUMBER(4,0)                                                 NaN            OPERACIONAL                        NaN
PCESTCOM         CODFUNC  NUMBER(8,0)                                                 NaN            OPERACIONAL                        NaN
PCESTCOM   NUMTRANSVENDA NUMBER(10,0)                                                 NaN            OPERACIONAL                        NaN
PCESTCOM       HISTORICO VARCHAR2(60)                                                 NaN            OPERACIONAL                        NaN
PCESTCOM          DTLANC         DATE                                                 NaN            OPERACIONAL                        NaN
PCESTCOM    VLESTORNOCMV NUMBER(18,6)                         Indica o valor estorno CMV.            OPERACIONAL                        NaN
PCESTCOM        CODUSUR2  NUMBER(6,0)           Indica o código do primeiro profissional.            OPERACIONAL                        NaN
PCESTCOM        CODUSUR3  NUMBER(6,0)            Indica o código do segundo profissional.            OPERACIONAL                        NaN
PCESTCOM        CODUSUR4  NUMBER(6,0)           Indica o código do terceiro profissional.            OPERACIONAL                        NaN
PCESTCOM      VLESTORNO2 NUMBER(14,2) Data de pagamento comisão do primeiro profissional.            OPERACIONAL                        NaN
PCESTCOM      VLESTORNO3 NUMBER(14,2)  Data de pagamento comisão do segundo profissional.            OPERACIONAL                        NaN
PCESTCOM      VLESTORNO4 NUMBER(14,2)  Data de pagamento comisão do segundo profissional.            OPERACIONAL                        NaN
PCESTCOM   DTPAGCOMISSAO         DATE Data de pagamento da comissão referente a devolução            OPERACIONAL                        NaN
PCESTCOM DTPAGCOMISSAOOP         DATE                  Fechamento de comissão do Operador            OPERACIONAL                        NaN
PCESTCOM      DTMXSALTER         DATE                                                 NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*