# 📊 Tabela: PCLFREGE115

### Estrutura de Colunas e Restrições

     Tabela          Coluna  Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLFREGE115          CODREG  NUMBER(10,0)                               Código do Registro.    CHAVE PRIMÁRIA (PK)                        NaN
PCLFREGE115    CODREGAJUSTE   VARCHAR2(8)         Código da informação adicional de ajuste.            OPERACIONAL                        NaN
PCLFREGE115     VALORAJUSTE  NUMBER(16,2) Valor referente à informação adicional de ajuste.            OPERACIONAL                        NaN
PCLFREGE115 DESCCOMPLAJUSTE VARCHAR2(200)                 Descrição complementar do ajuste.            OPERACIONAL                        NaN
PCLFREGE115       CODFILIAL   VARCHAR2(2)                                 Código da Filial.            OPERACIONAL                        NaN
PCLFREGE115         DATAINI          DATE                                     Data Inicial.            OPERACIONAL                        NaN
PCLFREGE115         DATAFIM          DATE                                       Data Final.            OPERACIONAL                        NaN
PCLFREGE115    ORIGEMAJUSTE  VARCHAR2(10)                                Origem ajuste E115            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*