# 📊 Tabela: PCDMPLFATOAGLUTINACAO

### Estrutura de Colunas e Restrições

               Tabela             Coluna  Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDMPLFATOAGLUTINACAO NUMFATOAGLUTINACAO  NUMBER(20,0) Sequencial Combinação Fato Contábil x Aglutinação    CHAVE PRIMÁRIA (PK)                        NaN
PCDMPLFATOAGLUTINACAO            CODDMPL  NUMBER(10,0)                                       Código DMPL CHAVE ESTRANGEIRA (FK)                     PCDMPL
PCDMPLFATOAGLUTINACAO    CODFATOCONTABIL  VARCHAR2(20)                              Código Fato Contábil            OPERACIONAL                        NaN
PCDMPLFATOAGLUTINACAO     CODAGLUTINACAO VARCHAR2(100)                                Código Aglutinação            OPERACIONAL                        NaN
PCDMPLFATOAGLUTINACAO      CODPLANOCONTA   NUMBER(5,0)                            Código Plano de Contas CHAVE ESTRANGEIRA (FK)               PCPLANOCONTA
PCDMPLFATOAGLUTINACAO         ORDEMLINHA   NUMBER(5,0)                                      Ordem Linnha            OPERACIONAL                        NaN
PCDMPLFATOAGLUTINACAO        ORDEMCOLUNA   NUMBER(5,0)                                      Ordem Coluna            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*