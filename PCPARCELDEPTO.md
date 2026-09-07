# 📊 Tabela: PCPARCELDEPTO

### Estrutura de Colunas e Restrições

       Tabela            Coluna Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARCELDEPTO         CODPARCEL  NUMBER(6,0)                            Sequêncial do registro    CHAVE PRIMÁRIA (PK)                        NaN
PCPARCELDEPTO         CODFILIAL  VARCHAR2(2)                                  Código da Filial            OPERACIONAL                        NaN
PCPARCELDEPTO          CODDEPTO  NUMBER(6,0)                            Código do Departamento            OPERACIONAL                        NaN
PCPARCELDEPTO            CODSEC  NUMBER(6,0)                                   Código da Seção            OPERACIONAL                        NaN
PCPARCELDEPTO      CODCATEGORIA  NUMBER(6,0)                               Código da Categoria            OPERACIONAL                        NaN
PCPARCELDEPTO   CODSUBCATEGORIA  NUMBER(6,0)                            Código da Subcategoria            OPERACIONAL                        NaN
PCPARCELDEPTO           CODPROD  NUMBER(6,0)                                 Código do produto            OPERACIONAL                        NaN
PCPARCELDEPTO      VLMINPARCELA  NUMBER(6,2)                          Valor mínimo da parcela             OPERACIONAL                        NaN
PCPARCELDEPTO      QTMAXPARCELA  NUMBER(4,0)                     Quantidade Máxima de Parcelas            OPERACIONAL                        NaN
PCPARCELDEPTO        VENCIMENTO  NUMBER(4,0)                Quantidade de Dias para vencimento            OPERACIONAL                        NaN
PCPARCELDEPTO        USADIAFIXO  VARCHAR2(1)                             Usar Dia Fixo (S / N)            OPERACIONAL                        NaN
PCPARCELDEPTO           DIAFIXO  NUMBER(2,0)                                          Dia Fixo            OPERACIONAL                        NaN
PCPARCELDEPTO          PERTXFIN  NUMBER(8,4)                      Valor de acréscimo/ desconto            OPERACIONAL                        NaN
PCPARCELDEPTO           TXJUROS  NUMBER(4,2)                            Valor da taxa de juros            OPERACIONAL                        NaN
PCPARCELDEPTO            STATUS  VARCHAR2(1)                                     Status(A / I)            OPERACIONAL                        NaN
PCPARCELDEPTO CODFUNCINATIVACAO  NUMBER(6,0) Código do Funcionário Responsável pela Inativação            OPERACIONAL                        NaN
PCPARCELDEPTO      DTINATIVACAO         DATE                                Data de Inativação            OPERACIONAL                        NaN
PCPARCELDEPTO  MOTIVOINATIVACAO VARCHAR2(90)                              Motivo da Inativação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*