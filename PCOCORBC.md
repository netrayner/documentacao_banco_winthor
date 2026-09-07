# 📊 Tabela: PCOCORBC

### Estrutura de Colunas e Restrições

  Tabela        Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCOCORBC      NUMBANCO   NUMBER(4,0)                                         NaN            OPERACIONAL                        NaN
PCOCORBC CODOCORRENCIA   VARCHAR2(3)                                         NaN            OPERACIONAL                        NaN
PCOCORBC    OCORRENCIA VARCHAR2(100)                                         NaN            OPERACIONAL                        NaN
PCOCORBC         BAIXA   VARCHAR2(1)                                         NaN            OPERACIONAL                        NaN
PCOCORBC        TARIFA  NUMBER(16,3)                                         NaN            OPERACIONAL                        NaN
PCOCORBC  OCORCARTORIO   VARCHAR2(1)                                         NaN            OPERACIONAL                        NaN
PCOCORBC      PROTESTO   VARCHAR2(1)            Indica a ocorrência de protesto.            OPERACIONAL                        NaN
PCOCORBC     TIPOOCORR   NUMBER(3,0)      Indica o tipo da ocorrência magnética.            OPERACIONAL                        NaN
PCOCORBC  CHDESCONTADO   VARCHAR2(1) Indica a ocorrência para cheque descontado.            OPERACIONAL                        NaN
PCOCORBC   CHDEVOLVIDO   VARCHAR2(1)  Indica a ocorrência para cheque devolvido.            OPERACIONAL                        NaN
PCOCORBC   GERARTARIFA   VARCHAR2(1)                    Gerar valores de tarifa?            OPERACIONAL                        NaN
PCOCORBC      CODBANCO   NUMBER(4,0)               Código do Banco da Ocorrência            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*