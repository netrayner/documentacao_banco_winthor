# 📊 Tabela: PCINDICADORESWMS

### Estrutura de Colunas e Restrições

          Tabela          Coluna   Tipo/Tamanho    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINDICADORESWMS       DESCRICAO  VARCHAR2(100) Descrição do indicador            OPERACIONAL                        NaN
PCINDICADORESWMS            RUIM   NUMBER(30,0)             Qtde. ruim            OPERACIONAL                        NaN
PCINDICADORESWMS        RAZOAVEL   NUMBER(30,0)         Qtde. razoavel            OPERACIONAL                        NaN
PCINDICADORESWMS             BOM   NUMBER(30,0)              Qtde. bom            OPERACIONAL                        NaN
PCINDICADORESWMS           OTIMO   NUMBER(30,0)            Qtde. otimo            OPERACIONAL                        NaN
PCINDICADORESWMS HABILITACOCKPIT    VARCHAR2(1)       Habilita cockpit            OPERACIONAL                        NaN
PCINDICADORESWMS       NUMINVENT VARCHAR2(4000)   Número do inventário            OPERACIONAL                        NaN
PCINDICADORESWMS      TIPOINVENT    VARCHAR2(1)     Tipo do Inventário            OPERACIONAL                        NaN
PCINDICADORESWMS       TIPODADOS  VARCHAR2(100)             Tipo dados            OPERACIONAL                        NaN
PCINDICADORESWMS  NOMECOMPONENTE  VARCHAR2(100)     Nome do componente            OPERACIONAL                        NaN
PCINDICADORESWMS            META   NUMBER(30,0)                   Meta            OPERACIONAL                        NaN
PCINDICADORESWMS       ORDENACAO    VARCHAR2(1)             Ordernação            OPERACIONAL                        NaN
PCINDICADORESWMS         CODFUNC    NUMBER(8,0)  Código do funcionário            OPERACIONAL                        NaN
PCINDICADORESWMS         PERIODO VARCHAR2(4000)                Período            OPERACIONAL                        NaN
PCINDICADORESWMS          FILIAL    VARCHAR2(3)    Filial do Indicador            OPERACIONAL                        NaN
PCINDICADORESWMS      FORNECEDOR VARCHAR2(4000)             Fornecedor            OPERACIONAL                        NaN
PCINDICADORESWMS      PARAMETROS VARCHAR2(4000)             parametros            OPERACIONAL                        NaN
PCINDICADORESWMS   VALPARAMETROS VARCHAR2(4000)       valor parametros            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*