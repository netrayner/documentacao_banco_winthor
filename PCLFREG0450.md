# 📊 Tabela: PCLFREG0450

### Estrutura de Colunas e Restrições

     Tabela      Coluna   Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLFREG0450      CODREG    NUMBER(6,0)          Indica o código do registro.    CHAVE PRIMÁRIA (PK)                        NaN
PCLFREG0450   CODFILIAL    VARCHAR2(2)            Indica o código da Filial.            OPERACIONAL                        NaN
PCLFREG0450         MES    NUMBER(2,0) Indica o mês a ser gerado no arquivo.            OPERACIONAL                        NaN
PCLFREG0450         ANO    NUMBER(4,0) Indica o ano a ser gerado no arquivo.            OPERACIONAL                        NaN
PCLFREG0450     TIPOMOV    VARCHAR2(1)           Indica o tipo de movimento.            OPERACIONAL                        NaN
PCLFREG0450      NUMCAR    NUMBER(8,0)      Indica o número de carregamento.            OPERACIONAL                        NaN
PCLFREG0450 NUMTRANSINI   NUMBER(10,0) Indica o número de transação inicial.            OPERACIONAL                        NaN
PCLFREG0450 NUMTRANSFIM   NUMBER(10,0)   Indica o número de transação final.            OPERACIONAL                        NaN
PCLFREG0450       TEXTO VARCHAR2(4000)          Indica o texto a ser gerado.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*