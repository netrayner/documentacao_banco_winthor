# 📊 Tabela: PCCONFFILIALSITUACAOESPECIAL

### Estrutura de Colunas e Restrições

                      Tabela               Coluna Tipo/Tamanho                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFFILIALSITUACAOESPECIAL     CODCONFEXERCICIO  NUMBER(8,0)                                               Código do Exercício Contábil            OPERACIONAL                        NaN
PCCONFFILIALSITUACAOESPECIAL                  ANO  NUMBER(4,0)                                                  Ano do Exercício Contábil            OPERACIONAL                        NaN
PCCONFFILIALSITUACAOESPECIAL       CODGRUPOFILIAL  NUMBER(5,0)                           Código do Grupo de Filiais do Exercício Contábil            OPERACIONAL                        NaN
PCCONFFILIALSITUACAOESPECIAL            CODFILIAL  VARCHAR2(2)                                                           Código da Filial            OPERACIONAL                        NaN
PCCONFFILIALSITUACAOESPECIAL     SITUACAOESPECIAL  NUMBER(8,0) Indicador de Situação Especial e Outros Eventos (conforme manual SPED ECF)            OPERACIONAL                        NaN
PCCONFFILIALSITUACAOESPECIAL DATASITUACAOESPECIAL         DATE                                                  Data da situação especial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*