# 📊 Tabela: PCDEVAVARIAC

### Estrutura de Colunas e Restrições

      Tabela          Coluna Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDEVAVARIAC   NUMTRANSVENDA NUMBER(10,0)                               Transação de saída avaria.    CHAVE PRIMÁRIA (PK)                        NaN
PCDEVAVARIAC       CODFORNEC  NUMBER(6,0)                             Código fornecedor a devolver            OPERACIONAL                        NaN
PCDEVAVARIAC            DATA         DATE                    Data/hora da geração da pré-devolução            OPERACIONAL                        NaN
PCDEVAVARIAC       CODFILIAL  VARCHAR2(2)                                                      NaN            OPERACIONAL                        NaN
PCDEVAVARIAC     CODFUNCLANC  NUMBER(8,0)                      Código do funcionário de lançamento            OPERACIONAL                        NaN
PCDEVAVARIAC      ROTINALANC  NUMBER(6,0)                           Código da rotina de lançamento            OPERACIONAL                        NaN
PCDEVAVARIAC  CODGRUPOAVARIA  NUMBER(6,0)                                     Cód. Grupo de Avaria            OPERACIONAL                        NaN
PCDEVAVARIAC      NUMREMESSA NUMBER(10,0) Número de remessa ao fornecedor do processo de garantia;            OPERACIONAL                        NaN
PCDEVAVARIAC DTEXPORTACAOWMS         DATE                                Data da exportação do WMS            OPERACIONAL                        NaN
PCDEVAVARIAC DTIMPORTACAOWMS         DATE                                Data de importação do WMS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*