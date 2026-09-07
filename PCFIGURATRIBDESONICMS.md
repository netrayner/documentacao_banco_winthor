# 📊 Tabela: PCFIGURATRIBDESONICMS

### Estrutura de Colunas e Restrições

               Tabela                         Coluna Tipo/Tamanho                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFIGURATRIBDESONICMS                         CODIGO  NUMBER(8,0)                                                                               Código    CHAVE PRIMÁRIA (PK)                        NaN
PCFIGURATRIBDESONICMS                      DESCRICAO VARCHAR2(50)                                                                            Descrição            OPERACIONAL                        NaN
PCFIGURATRIBDESONICMS                            CST  NUMBER(3,0)                                                                                  Cst            OPERACIONAL                        NaN
PCFIGURATRIBDESONICMS              MOTIVODESONERACAO  NUMBER(3,0)                                                                Motivo da desoneração            OPERACIONAL                        NaN
PCFIGURATRIBDESONICMS                      CODFILIAL  VARCHAR2(2)                                                                        Código Filial            OPERACIONAL                        NaN
PCFIGURATRIBDESONICMS                    TIPOCLIENTE  VARCHAR2(5)                                                                                  NaN            OPERACIONAL                        NaN
PCFIGURATRIBDESONICMS          CODFILIALFIGURAORIGEM  NUMBER(8,0)                                                                                  NaN            OPERACIONAL                        NaN
PCFIGURATRIBDESONICMS                CODFIGURAORIGEM  VARCHAR2(2)                                                                                  NaN            OPERACIONAL                        NaN
PCFIGURATRIBDESONICMS DESCONSIDERAR_SUFRAMA_DESCICMS  VARCHAR2(1) Desconsidera o valor suframa ou desconto de icms da base de cálculo para desoneração            OPERACIONAL                        NaN
PCFIGURATRIBDESONICMS     INCLUIRICMSBASEDESONERACAO  VARCHAR2(1)                            Incluir percentual de icms normal na base da desoneração.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*