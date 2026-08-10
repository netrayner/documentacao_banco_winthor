# 📊 Tabela: PCFICHAREST

### Estrutura de Colunas e Restrições

     Tabela          Coluna Tipo/Tamanho                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFICHAREST       CODFILIAL  VARCHAR2(2)                                                 Código Filial            OPERACIONAL                        NaN
PCFICHAREST        NUMFICHA NUMBER(10,0)                                               Número da ficha            OPERACIONAL                        NaN
PCFICHAREST      DTINCLUSAO         DATE                                                 Data inclusão            OPERACIONAL                        NaN
PCFICHAREST      DTULTVENDA         DATE                              Data da última venda com a ficha            OPERACIONAL                        NaN
PCFICHAREST      CODFUNCINC  NUMBER(8,0)                     Código do funcionário que incluiu a ficha            OPERACIONAL                        NaN
PCFICHAREST CODFUNCULTVENDA  NUMBER(8,0) Código do funcionário que realizou a última venda com a ficha            OPERACIONAL                        NaN
PCFICHAREST        DTINATIV         DATE                                            Data da inativação            OPERACIONAL                        NaN
PCFICHAREST             OBS VARCHAR2(80)                                                    Observação            OPERACIONAL                        NaN
PCFICHAREST   CODFUNCINATIV  NUMBER(8,0)                   Código do funcionário que desativou a ficha            OPERACIONAL                        NaN
PCFICHAREST            TIPO  VARCHAR2(1)                                       Tipo Ficha ou Tipo Mesa            OPERACIONAL                        NaN
PCFICHAREST      CODINTERNO NUMBER(10,0)                     Código interno da ficha dentro da Catraca            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*