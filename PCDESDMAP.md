# 📊 Tabela: PCDESDMAP

### Estrutura de Colunas e Restrições

   Tabela            Coluna  Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESDMAP          PROCESSO VARCHAR2(200)                     Indica o processo que gerou o desdobramento            OPERACIONAL                        NaN
PCDESDMAP NUMTRANSVENDADEST  NUMBER(22,0)                               Indica o numtransvenda de destino            OPERACIONAL                        NaN
PCDESDMAP         PRESTDEST   VARCHAR2(2)                                       Indica a prest de destino            OPERACIONAL                        NaN
PCDESDMAP NUMTRANSVENDAORIG  NUMBER(22,0)                               Inidica o numtransvenda de origem            OPERACIONAL                        NaN
PCDESDMAP         PRESTORIG   VARCHAR2(2)                                        Indica a prest de origem            OPERACIONAL                        NaN
PCDESDMAP            DTLANC          DATE Data que aconteceu o desdobramento, da mesma forma que a PCDESD            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*