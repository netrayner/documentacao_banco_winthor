# 📊 Tabela: PCCOTACAOIMP

### Estrutura de Colunas e Restrições

      Tabela        Coluna   Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOTACAOIMP    NUMCOTACAO    NUMBER(8,0)                          Número da cotação    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTACAOIMP DTINIVIGENCIA           DATE                 Data do início da vigência            OPERACIONAL                        NaN
PCCOTACAOIMP DTFIMVIGENCIA           DATE                       Data fim da vigência            OPERACIONAL                        NaN
PCCOTACAOIMP    DTCADASTRO           DATE                           Data de cadastro            OPERACIONAL                        NaN
PCCOTACAOIMP   CODFUNCLANC    NUMBER(8,0) Código do funonário que efetuou o cadastro            OPERACIONAL                        NaN
PCCOTACAOIMP     CODROTINA    NUMBER(8,0)    Código da rotina que efetuou o cadastro            OPERACIONAL                        NaN
PCCOTACAOIMP      SITUACAO        CHAR(1)  Situação do pedido (Aberto/Fechado/Ambos)            OPERACIONAL                        NaN
PCCOTACAOIMP  DTFECHAMENTO           DATE              Data de fechamento da cotação            OPERACIONAL                        NaN
PCCOTACAOIMP    OBSERVACAO VARCHAR2(4000)             Observação referente a cotação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*