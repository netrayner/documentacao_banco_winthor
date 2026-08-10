# 📊 Tabela: PCBINCARTAO

### Estrutura de Colunas e Restrições

     Tabela        Coluna Tipo/Tamanho                                                                                                                                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBINCARTAO  CODBINCARTAO  NUMBER(9,0)                                                                                                                                                                                      Chave primária    CHAVE PRIMÁRIA (PK)                        NaN
PCBINCARTAO NROBININICIAL  NUMBER(9,0)                                                                                                                                                                     Número do BIN do cartão inicial            OPERACIONAL                        NaN
PCBINCARTAO   NROBINFINAL  NUMBER(9,0)                                                                                                                                                                       Número do BIN do cartão final            OPERACIONAL                        NaN
PCBINCARTAO       CODREDE  VARCHAR2(5)                                                                                                                                                                            Código da rede do cartão            OPERACIONAL                        NaN
PCBINCARTAO   CODBANDEIRA  VARCHAR2(6)                                                                                                                                                                        Código da bandeira do cartão            OPERACIONAL                        NaN
PCBINCARTAO          TIPO  NUMBER(2,0) 0 - cartão crédito, 1 - cartão débito, 3 - cartão alimentação, 4 - cartão refeição, 5 - cartão fidelidade, 6 - cartão tipo voucher, 7 - cartão benefício, 8 - cartão combustível, 99 - outros tipos            OPERACIONAL                        NaN
PCBINCARTAO    DTEXCLUSAO         DATE                                                                                                                                                                          Data da exclusão do cartão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*