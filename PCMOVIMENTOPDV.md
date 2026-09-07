# 📊 Tabela: PCMOVIMENTOPDV

### Estrutura de Colunas e Restrições

        Tabela                    Coluna Tipo/Tamanho                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVIMENTOPDV           NUMMOVIMENTOPDV NUMBER(10,0)                                              Chave primária da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVIMENTOPDV                  NUMCAIXA  NUMBER(4,0)                                                       Número do Caixa    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVIMENTOPDV                DTABERTURA         DATE                                                      Data de abertura            OPERACIONAL                        NaN
PCMOVIMENTOPDV               DTMOVIMENTO         DATE                                                     Data do movimento            OPERACIONAL                        NaN
PCMOVIMENTOPDV           CODFUNCABERTURA  NUMBER(8,0)                         Código do funcionário que realizou a abertura            OPERACIONAL                        NaN
PCMOVIMENTOPDV              DTFECHAMENTO         DATE                                                    Data do fechamento            OPERACIONAL                        NaN
PCMOVIMENTOPDV         CODFUNCFECHAMENTO  NUMBER(8,0)                       Código do funcionário que realizou o fechamento            OPERACIONAL                        NaN
PCMOVIMENTOPDV                 EXPORTADO  VARCHAR2(1)                                        Define se foi exportado ou não            OPERACIONAL                        NaN
PCMOVIMENTOPDV OFERTATERCEIROSPROCESSADA  VARCHAR2(1)                        Indica se teve oferta foi procssada pelo motor            OPERACIONAL                        NaN
PCMOVIMENTOPDV                  QTVENDAS NUMBER(10,0)                          Quantidade de Vendas realizadas no movimento            OPERACIONAL                        NaN
PCMOVIMENTOPDV            QTCANCELAMENTO NUMBER(10,0)                   Quantidade de Cancelamentos realizados no movimento            OPERACIONAL                        NaN
PCMOVIMENTOPDV             VLTOTALVENDAS NUMBER(10,2)                        Valor total das vendas realizadas no movimento            OPERACIONAL                        NaN
PCMOVIMENTOPDV      MOVIMENTOCONSISTENTE  VARCHAR2(1) Indica se todas as transações do movimento foram inseridas no Winthor            OPERACIONAL                        NaN
PCMOVIMENTOPDV                 CODFILIAL  VARCHAR2(3)                    Código da filial que o caixa do movimento pertence            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*