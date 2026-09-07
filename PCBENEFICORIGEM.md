# 📊 Tabela: PCBENEFICORIGEM

### Estrutura de Colunas e Restrições

         Tabela                  Coluna Tipo/Tamanho                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBENEFICORIGEM                  NUMPED NUMBER(10,0)                                                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCBENEFICORIGEM                 CODPROD  NUMBER(6,0)                                                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCBENEFICORIGEM                      QT NUMBER(10,4)                                                                       NaN            OPERACIONAL                        NaN
PCBENEFICORIGEM                   PUNIT NUMBER(18,6)                                                                       NaN            OPERACIONAL                        NaN
PCBENEFICORIGEM              QTENTREGUE NUMBER(10,4)                                                                       NaN            OPERACIONAL                        NaN
PCBENEFICORIGEM                 PERCIPI  NUMBER(8,4)  Contém o valor do percentual de IPI informado para o produto de origem.             OPERACIONAL                        NaN
PCBENEFICORIGEM                 PERCICM  NUMBER(8,4) Contém o valor do percentual de ICMS informado para o produto de origem.             OPERACIONAL                        NaN
PCBENEFICORIGEM                      ST NUMBER(12,6)                 Contém o valor do ST informado para o produto de origem.             OPERACIONAL                        NaN
PCBENEFICORIGEM                BASEICST NUMBER(12,6)         Contém o valor da base do ST informado para o produto de origem.             OPERACIONAL                        NaN
PCBENEFICORIGEM               SITTRIBUT  VARCHAR2(3)         Contém a situação tributária informada para o produto de origem.             OPERACIONAL                        NaN
PCBENEFICORIGEM               CODFISCAL  NUMBER(8,0)                                                  Indica o código fiscal.             OPERACIONAL                        NaN
PCBENEFICORIGEM                 QTPERDA NUMBER(14,8)                                             Quantidade perda de insumos.             OPERACIONAL                        NaN
PCBENEFICORIGEM CODMOTIVOICMSDESONERADO  VARCHAR2(2)                                   Código do Motivo da Desoneração do ICMS            OPERACIONAL                        NaN
PCBENEFICORIGEM       VLICMSDESONERACAO NUMBER(18,6)                                                  Valor do ICMS Desonerado            OPERACIONAL                        NaN
PCBENEFICORIGEM                 CODCEST  VARCHAR2(7)                                                                       NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*